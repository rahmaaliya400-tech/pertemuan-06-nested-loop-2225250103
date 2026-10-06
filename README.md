# Pertemuan 06 Nested Loop Python
Algoritma dan Pemrograman | Pertemuan 06 | 12

Nama: Rahma Aliya
NIM: 2225250103
Kelas: 3F
## Tujuan
Menggunakan nested loop, pola, akumulasi, dan pencacahan.
## Cara Menjalankan
python3 tugas/tabel_perkalian_dan_statistik.py
## Algoritma Tugas 3
Loop luar digunakan untuk mengatur baris pada tabel perkalian.
Loop dalam digunakan untuk mengatur kolom pada setiap baris.
total_baris digunakan untuk menghitung jumlah hasil perkalian pada setiap baris.
total_semua digunakan untuk menghitung jumlah seluruh hasil perkalian.
count_genap digunakan untuk menghitung banyak hasil perkalian yang bernilai genap.
## Hasil Pengujian
| Input | Hasil yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|
| n = 1 | Total = 1, Genap = 0 | Total = 1, Genap = 0 | Berhasil |
| n = 2 | Total = 9, Genap = 3 | Total = 9, Genap = 3 | Berhasil |
| n = 3 | Total = 36, Genap = 5 | Total = 36, Genap = 5 | Berhasil |
| n = 0 | Meminta input kembali | Meminta input kembali | Berhasil |
## Analisis Efisiensi
Untuk input n, loop luar berjalan sebanyak n kali dan loop dalam juga berjalan sebanyak n kali untuk setiap iterasi loop luar. Oleh karena itu, badan loop dalam dijalankan sebanyak n × n atau n² kali.
## Refleksi
Salah satu hal yang perlu diperhatikan pada nested loop adalah posisi inisialisasi akumulator. total_baris harus direset menjadi 0 pada setiap awal iterasi loop luar agar jumlah setiap baris dapat dihitung dengan benar. Sedangkan total_semua diinisialisasi sebelum kedua loop agar dapat menghitung jumlah seluruh hasil perkalian.