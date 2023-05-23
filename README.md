## Starting The Game

1. clone repositori ini:

```bash
git clone https://github.com/mzmunechika/python_for_beginners.git
```

Jika anda menggunakan ssh:

```bash
git clone git@github.com:mzmunechika/python_for_beginners.git
```

2. buat branch baru dengan nama anda, contoh:

```bash
git checkout -b rie
```

3. kerjakan soalnya

## How to learn from here (Cara belajar dari sini)

Langsung aja mulai dari [sini](./day_1/1_get_started.md)

## Flow (Alur)

`main` :

- variable.py `(soal)`
- data_types.py `(soal)`
- array.py `(soal)`
- comments.py `(soal)`
- ...

```bash
git clone https://github.com/some_repo
```

---

`your_branch1` :

```bash
git checkout -b your_branch1
```

- variable.py `(jawaban b1)`
- data_types.py `(jawaban b1)`
- array.py `(jawaban b1)`
- comments.py `(jawaban b1)`
- ...

```bash
git push origin your_branch1
```

---

`your_branch2` :

```bash
git checkout -b your_branch2
```

- variable.py `(jawaban b2)`
- data_types.py `(jawaban b2)`
- array.py `(jawaban b2)`
- comments.py `(jawaban b2)`
- ...

```bash
git push origin your_branch2
```

```mermaid
flowchart TD
M[main] -- start here --> A[clone] --> B[local A]
A --> C[local B]
B --> D[checkout -b branch1]
C --> E[checkout -b branch2]
D --> F[push origin branch1]
E --> G[push origin branch2]
```
