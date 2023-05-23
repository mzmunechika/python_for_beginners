## Baby Step

Melakukan clone repositori dengan HTTPS:

```bash
git clone https://github.com/nama_akun/nama_repositori.git
```

Melakukan clone dengan SSH:

```bash
git@github.com:nama_akun/nama_repositori.git
```

## Sebelum Membuat Perubahan Pada File Setelah Melakukan Cloning

Sebelum membuat peruahan pada file yang akan dipush setelah kamu melakukan cloning, kamu harus cek branch kamu terlebih dahulu, apakah kamu sudah berada pada branch kamu atau belum?

Oh iya, kita akan menggunakan syntax/simbol `&&` untuk sekaligus menjalankan 2 perintah. <span style="text-decoration:underline">Perintah pertama</span> untuk update branch jarak jauh, dan <span style="text-decoration:underline">perintah kedua</span> untuk melihat seluruh branch yang telah di push, jalankan perintahnya:

> Ketika kamu melihat branch yang berwarna hijau, tandanya kamu sedang berada di branch tersebut.

```bash
git fetch && git branch -a
```

Kita asumsikan kamu <span style="text-decoration:underline">belum membuat branch</span>, di sini kita akan membuat branch sekaligus masuk kedalam branch yang kita buat, jalankan perintahnya:

> Sudah membuat branch? lewati satu langkah di bawah ini.

```bash
git checkout -b nama_branch_kamu
```

Setelah itu, silahkan edit filenya.

## Langkah Push[^1] kedalam Repositori Jarak Jauh (non local)

Ketika kamu telah selesai melakukan satu sesi tugas, dan kamu ingin melakukan push pada repositori jarak jauh, langkah pertama yang harus kamu lakukan adalah memriksa file apa saja yang telah dilakukan perubahan di dalamnya, jalankan perintahnya:

> Biasanya file yang telah diubah (diedit, ditambahkan, dihapus, atau apapun itu) akan berwarna merah.

```bash
git status
```

Tambahkan file yang telah dirubah untuk di push, jalankan perintahnya:

> Ini adalah teknik menambahkan file satu-persatu, biasanya saya sering melakukan ini untuk menambahkan commit yang berbeda.

```bash
git add nama_file
```

Jika kamu ingin menambahkan semua filenya dan tidak mau menambahkannya satu-persatu, jalankan perintahnya:

> Kekurangan dari perintah ini adalah, kita tidak bisa memberikan commit/deskripsi satu-persatu dari perubahan file yang telah kita ubah.

```bash
git add .
```

Setelah file ditambahkan, kita akan membuat sebuah commit[^2], jalankan perintahnya:

> Commit yang baik adalah commit yang memiliki deskripsi yang jelas dan informatif tentang perubahan yang dilakukan. Deskripsi tersebut sebaiknya menjelaskan secara singkat apa yang diubah, mengapa perubahan tersebut dilakukan, dan mungkin juga mencakup konteks atau rujukan tambahan yang relevan.

```bash
git commit -m "tuliskan deskripsi singkat perubahan pada file kamu di sini"
```

File yang sudah kamu ubah atau edit telah kamu beri commit. Selanjutnya, mari kita push dengan branchmu sendiri, jalankan perintahnya:

```bash
git push origin nama_branch_kamu
```

Lakukan urutan perintah yang sama ketika ingin melakukan push.

## Footnotes

[^1]: Push dalam Git adalah perintah yang digunakan untuk mengirimkan perubahan yang terjadi pada repositori lokal ke repositori jarak jauh (remote repository) yang terhubung, sehingga memperbarui dan menyinkronkan kode di antara kedua repositori tersebut.
[^2]: Commit pada Git adalah tindakan untuk menyimpan perubahan-perubahan pada repositori lokal dengan memberikan pesan deskriptif yang merepresentasikan rangkuman dari perubahan yang dilakukan.
