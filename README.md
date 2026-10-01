# Pertemuan 05 Perulangan Python

**Nama:** Sela Widiyanti
**NIM:** 2225250176
**Kelas:** 3F

## Tujuan

Mempelajari dan menggunakan perulangan `for` dan `while` dalam Python untuk menyelesaikan masalah iteratif, melakukan validasi input, menggunakan seleksi di dalam perulangan, serta melakukan akumulasi dan pencacahan.

## Cara Menjalankan

Program dapat dijalankan melalui terminal VS Code dengan perintah:

```bash
python latihan/01_tabel_perkalian.py
python latihan/02_jumlah_bilangan.py
python latihan/03_validasi_input.py
python latihan/04_hitung_genap.py
python kuis/kuis2_deret_aritmetika.py
```

## Daftar Program

### Latihan 1 - Tabel Perkalian

Program menerima sebuah bilangan bulat dan menampilkan hasil perkalian bilangan tersebut dari 1 sampai 10 menggunakan perulangan `for`.

### Latihan 2 - Jumlah Bilangan

Program menerima bilangan positif `n`, kemudian menghitung jumlah bilangan dari 1 sampai `n` menggunakan `for` dan akumulasi.

### Latihan 3 - Validasi Input

Program meminta nilai ujian antara 0 sampai 100. Jika nilai berada di luar rentang tersebut, program akan meminta input kembali menggunakan `while` sampai mendapatkan nilai yang valid.

### Latihan 4 - Menghitung Bilangan Genap

Program menghitung banyaknya bilangan genap dari 1 sampai `n` menggunakan perulangan `for` dan seleksi `if`.

## Algoritma Kuis 2

1. Memasukkan suku pertama `a`.
2. Memasukkan beda `d`.
3. Memasukkan banyak suku `n`.
4. Memeriksa nilai `n` menggunakan `while`.
5. Jika `n` kurang dari atau sama dengan 0, program meminta input `n` kembali.
6. Menginisialisasi `total = 0`.
7. Menggunakan `for` sebanyak `n` kali.
8. Menghitung setiap suku dengan `a + i * d`.
9. Menambahkan setiap suku ke dalam `total`.
10. Menampilkan setiap suku.
11. Setelah perulangan selesai, menampilkan jumlah seluruh suku.

## Hasil Pengujian

### Kuis 2

| Test Case | Input             | Hasil yang Diharapkan               | Status   |
| --------- | ----------------- | ----------------------------------- | -------- |
| 1         | a=2, d=3, n=5     | Suku: 2, 5, 8, 11, 14; Jumlah=40.00 | Berhasil |
| 2         | a=10, d=-2, n=4   | Suku: 10, 8, 6, 4; Jumlah=28.00     | Berhasil |
| 3         | a=1.5, d=0.5, n=3 | Suku: 1.5, 2.0, 2.5; Jumlah=6.00    | Berhasil |

### Latihan

| Program         | Test Case   | Hasil                           |
| --------------- | ----------- | ------------------------------- |
| Tabel Perkalian | n=4         | Berhasil, menghasilkan 10 baris |
| Tabel Perkalian | n=-3        | Berhasil, menghasilkan 10 baris |
| Jumlah Bilangan | n=1         | 1                               |
| Jumlah Bilangan | n=5         | 15                              |
| Validasi Input  | 120, -5, 75 | 120 dan -5 ditolak, 75 diterima |
| Hitung Genap    | n=10        | 5                               |

## Refleksi

Kesalahan yang perlu diperhatikan dalam perulangan adalah kesalahan batas `range`, variabel kontrol `while` yang tidak diperbarui, dan akumulator yang diletakkan di dalam loop sehingga nilainya terus direset.

Pada Kuis 2, `while` digunakan untuk validasi nilai `n` karena jumlah percobaan input tidak diketahui. Setelah nilai `n` valid, `for` digunakan karena jumlah iterasi sudah diketahui, yaitu sebanyak `n` kali.

Saya juga belajar bahwa `total` harus diinisialisasi sebelum perulangan agar nilai hasil akumulasi tidak kembali menjadi 0 pada setiap iterasi.

## Kesimpulan

Pada Pertemuan 05 saya mempelajari penggunaan `for`, `while`, `range`, seleksi di dalam perulangan, akumulasi, pencacahan, validasi input, serta pengujian program. Saya juga belajar melakukan tracing dan debugging perulangan di VS Code serta mengunggah hasil pekerjaan ke GitHub.
