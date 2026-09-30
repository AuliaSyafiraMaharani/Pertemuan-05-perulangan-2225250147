# Pertemuan 05 Perulangan Python

Nama: Aulia Syafira Maharani
NIM: 2225250147
Kelas: 3A

## Tujuan

Menggunakan perulangan for dan while untuk menyelesaikan masalah iteratif.
Memahami kondisi berhenti, perubahan variabel, akumulasi, dan pencacahan.

## Struktur Folder

- latihan/
  - 01_tabel_perkalian.py
  - 02_jumlah_bilangan.py
  - 03_validasi_input.py
  - 04_hitung_genap.py
- kuis/
  - kuis2_deret_aritmetika.py
- README.md
- .gitignore

## Latihan

### 1. Tabel Perkalian

Program menerima satu bilangan kemudian menampilkan perkalian
dari 1 sampai 10 menggunakan for.

### 2. Jumlah Bilangan

Program menerima bilangan positif n kemudian menghitung jumlah
bilangan dari 1 sampai n menggunakan for.

### 3. Validasi Input

Program meminta nilai antara 0 sampai 100.
Jika nilai tidak valid, program akan meminta input kembali
menggunakan while.

### 4. Menghitung Bilangan Genap

Program menghitung banyak bilangan genap dari 1 sampai n
menggunakan for dan if.

## Tujuan Kuis 2

Membuat program deret aritmetika menggunakan perulangan.
Program menggunakan while untuk memvalidasi banyak suku dan
for untuk menghasilkan suku serta menghitung jumlah deret.

## Cara Menjalankan

Untuk menjalankan latihan:

python latihan/01_tabel_perkalian.py

python latihan/02_jumlah_bilangan.py

python latihan/03_validasi_input.py

python latihan/04_hitung_genap.py

Untuk menjalankan Kuis 2:

python kuis/kuis2_deret_aritmetika.py

## Algoritma Kuis 2

1. Memasukkan suku pertama a.
2. Memasukkan beda d.
3. Memasukkan banyak suku n.
4. Jika n kurang dari atau sama dengan 0, input n diminta kembali.
5. Menentukan total awal sebesar 0.
6. Menggunakan for sebanyak n kali.
7. Menghitung setiap suku dengan a + i * d.
8. Menambahkan setiap suku ke total.
9. Menampilkan setiap suku.
10. Menampilkan jumlah seluruh suku.

## Hasil Pengujian

| Program | Input | Hasil |
|---|---|---|
| Tabel Perkalian | n = 4 | 10 baris perkalian |
| Jumlah Bilangan | n = 5 | Jumlah = 15 |
| Validasi Input | 120, -5, 75 | Nilai diterima = 75 |
| Hitung Genap | n = 10 | Banyak bilangan genap = 5 |
| Kuis 2 | a=2, d=3, n=5 | Jumlah = 40 |
| Kuis 2 | a=10, d=-2, n=4 | Jumlah = 28 |
| Kuis 2 | a=1.5, d=0.5, n=3 | Jumlah = 6.00 |

## Refleksi

Kesalahan yang ditemukan adalah kesalahan pada batas perulangan.
Kesalahan tersebut dapat diperbaiki dengan memeriksa kembali nilai
awal, kondisi, dan pembaruan variabel.

Saya memahami bahwa for lebih sesuai ketika jumlah iterasi sudah
diketahui, sedangkan while digunakan ketika perulangan dikendalikan
oleh suatu kondisi.

## Kesimpulan

Pada Pertemuan 05 saya mempelajari penggunaan for dan while,
kondisi berhenti, akumulasi, pencacahan, validasi input berulang,
serta penggunaan if di dalam perulangan.

## Sumber

- Materi Pertemuan 05 Algoritma dan Pemrograman, Program Studi
  S1 Pendidikan Matematika FKIP Untirta, Tahun Ajaran 2026/2027.
- Python Software Foundation, Python 3 Documentation.