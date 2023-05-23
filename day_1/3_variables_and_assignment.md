## Variables and Assignment

Variabel adalah sebuah nama yang digunakan untuk menyimpan nilai atau data dalam program. Variabel memungkinkan kita untuk menyimpan dan mengakses data dengan mudah. Di Python, variabel tidak perlu dideklarasikan secara eksplisit sebelum digunakan. Kita bisa langsung membuat variabel dan memberikan nilai kepadanya menggunakan operator assignment.

Operator assignment (`=`) digunakan untuk memberikan nilai ke variabel. Nilai yang diberikan dapat berupa angka, string, atau tipe data lainnya. Berikut adalah contoh penggunaan operator assignment untuk membuat variabel dan memberikan nilai:

```python
x = 10
name = "John"
```

Pada contoh di atas, variabel `x` diberikan nilai 10, dan variabel `name` diberikan nilai "John". Setelah variabel didefinisikan, kita bisa menggunakannya dalam program.

Python adalah bahasa pemrograman dengan aturan penamaan variabel yang fleksibel. Beberapa aturan dalam penamaan variabel di Python adalah sebagai berikut:

- Nama variabel harus dimulai dengan huruf atau garis bawah (\_).
- Nama variabel hanya boleh mengandung huruf (baik huruf besar maupun huruf kecil), angka, dan garis bawah (\_).
- Nama variabel bersifat case-sensitive, artinya huruf besar dan huruf kecil dianggap berbeda.
- Tidak diperbolehkan menggunakan kata-kata kunci (keyword) yang sudah ada dalam Python sebagai nama variabel.

Contoh penggunaan variabel dalam Python:

```python
x = 10
y = 5
z = x + y
print(z)
```

Pada contoh di atas, variabel `x` diberikan nilai 10, variabel `y` diberikan nilai 5, dan variabel `z` diberikan hasil penjumlahan `x` dan `y`. Kemudian, hasil penjumlahan tersebut ditampilkan menggunakan fungsi `print()`.

Melalui penggunaan variabel dan assignment, kita dapat mengubah nilai variabel sepanjang program berjalan. Contohnya:

```python
x = 10
print(x)  # Output: 10

x = 20
print(x)  # Output: 20
```

Pada contoh di atas, nilai variabel `x` diubah menjadi 20 setelahnya, dan hasil dari `print(x)` juga berubah sesuai dengan nilai yang baru.

Variabel juga bisa digunakan dalam operasi matematika dan manipulasi string. Contoh penggunaan variabel dalam operasi matematika:

```python
x = 5
y = 3
z = x * y + 2
print(z)
```

Pada contoh di atas, variabel `z` diberikan hasil dari operasi matematika (`x * y + 2`).

Contoh penggunaan variabel dalam manipulasi string:

```python
name = "John"
greeting = "Hi, " + name + "!"
print(greeting)
```

Pada contoh di atas, variabel `greeting` diberikan hasil dari penggabungan string menggunakan operator concatenation (`+`).

Penggunaan variabel dan assignment sangat penting dalam pemrograman Python karena memungkinkan kita untuk menyimpan dan memanipulasi data dengan lebih efisien. Dengan variabel,

Dalam Python, Anda tidak perlu mendeklarasikan tipe data variabel. Python akan secara otomatis menentukan tipe data variabel berdasarkan nilai yang diberikan pada variabel tersebut. Anda juga dapat mengetahui tipe data variabel dengan menggunakan fungsi `type()`. Contoh:

```python
x = 10
y = "Hello, World!"
print(type(x))  # int
print(type(y))  # str
```

Dengan memahami konsep variabel dan assignment pada Python, Anda dapat membuat program yang lebih kompleks dan efisien dengan menggunakan variabel untuk menyimpan data dan melakukan operasi atau manipulasi data.

## Latihan

1. Apa yang dimaksud dengan variabel dalam pemrograman Python?
2. Apa yang dilakukan oleh operator assignment (`=`) dalam Python?
3. Bagaimana cara membuat variabel `x` dan memberikan nilai 10 kepadanya?
4. Berapa nilai dari variabel `name` jika diberikan nilai "Alice"?
5. Apakah yang terjadi jika kita menggunakan kata-kunci Python sebagai nama variabel?
6. Apa yang dimaksud dengan penamaan variabel yang bersifat case-sensitive?
7. Bagaimana cara mengubah nilai variabel yang sudah didefinisikan sebelumnya?
8. Apa hasil dari operasi `x * y + 2` jika `x = 4` dan `y = 3`?
9. Berapakah hasil dari operasi `x + y` jika `x = 5` (integer) dan `y = "3"` (string)?
10. Bagaimana cara menggabungkan dua string menggunakan operator concatenation dalam Python?

## Cara Menjawab Materi Ini

Tolong perhatikan dan ikuti intruksi dengan benar.

1. Buka direktori atau folder `/day_1/your_code`
2. Buatlah sebuah file bernama `answer_3.py`
3. Tulis jawaban di dalam file yang berekstensi `.py`/python.
