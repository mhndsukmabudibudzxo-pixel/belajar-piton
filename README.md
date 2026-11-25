[README.md](https://github.com/user-attachments/files/35418173/README.md)
# Belajar Dasar Python

Kumpulan latihan dasar pemrograman Python yang saya kerjakan selama belajar. Setiap file berisi contoh kode singkat beserta komentar penjelasan.

## Materi

| No | Topik | Isi |
|----|-------|-----|
| 1 | Hello World | Mencetak teks pertama dengan `print()` |
| 2 | Variabel dan Tipe Data | Integer, float, string, dan boolean |
| 3 | Operator | Aritmatika, perbandingan, dan logika (`and`, `or`, `not`) |
| 4 | Indentasi | Aturan penulisan blok kode pada Python |
| 5 | Lists | Mengakses (indexing), menambah, menghapus, dan menggabungkan item |
| 6 | Dictionaries | Mengakses, menambah, mengubah, dan menghapus item |
| 7 | Class dan Object | Property, constructor (`__init__`), dan method |

## Prasyarat

- [Python 3](https://www.python.org/downloads/) terpasang
- Code editor seperti Visual Studio Code, Atom, atau Notepad++

Cek versi Python:

```bash
python --version
```

## Cara Menjalankan

1. Clone repositori ini:

   ```bash
   git clone https://github.com/<username>/<nama-repo>.git
   cd <nama-repo>
   ```

2. Jalankan file yang diinginkan:

   ```bash
   python nama_file.py
   ```

   Contoh:

   ```bash
   python variable_numbers.py
   ```

## Contoh Kode

```python
class Cat:
    color = "black"

    def __init__(self, color):
        self.color = color

    def say(self):
        print("My color is %s" % self.color)

cat1 = Cat("orange")
cat1.say()  # My color is orange
```

## Konvensi Commit

Repositori ini memakai [Conventional Commits](https://www.conventionalcommits.org/), contohnya:

```
feat: add python lists and dictionaries examples
```

## Catatan

- Beberapa file sengaja berisi contoh penulisan yang salah (misalnya `true` huruf kecil atau indentasi yang keliru) untuk menunjukkan error yang muncul.
- Repositori ini dibuat untuk keperluan belajar.

## Lisensi

Bebas digunakan untuk keperluan belajar.
