# Pertemuan 09 - List dan Pengolahan Data Numerik

Nama: Mafatihun Nabila
NIM: 2225250198
Kelas: 3B

## Tujuan

Mengolah kumpulan data numerik menggunakan list Python, memahami indeks dan slicing, memanipulasi list, menghitung statistik, memfilter nilai kelulusan, serta membuat fungsi untuk mengolah data.

## Struktur Program

Program pada pertemuan ini terdiri dari beberapa file latihan dan satu file praktik.

1. `01_buat_list.py` – Membuat list dan menghitung jumlah elemen.
2. `02_indeks_slicing.py` – Mengakses elemen menggunakan indeks dan slicing.
3. `03_manipulasi_list.py` – Mengubah, menambahkan, menyisipkan, dan menghapus elemen list.
4. `04_agregasi_nilai.py` – Menghitung total, rata-rata, nilai minimum, dan maksimum.
5. `05_filter_kelulusan.py` – Menampilkan nilai yang memenuhi batas kelulusan.
6. `06_fungsi_statistik.py` – Membuat fungsi untuk menghitung rata-rata.
7. `praktik/analisis_nilai_mahasiswa.py` – Menganalisis nilai mahasiswa, menghitung statistik, dan menentukan jumlah mahasiswa yang lulus serta belum lulus.

## Cara Menjalankan

Jalankan program praktik melalui terminal dengan perintah:

```bash
python3 praktik/analisis_nilai_mahasiswa.py
```

Pastikan terminal berada di direktori utama proyek.

## Test Case

| Data | Pengujian | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| `[60, 70, 80]` | Rata-rata | 70.00 | 70.00 | Berhasil |
| `[60, 70, 80]` | Minimum dan maksimum | 60 / 80 | 60 / 80 | Berhasil |
| `[60, 70, 80]` | Jumlah lulus | 3 | 3 | Berhasil |
| `[59, 60, 61]` | Batas kelulusan 60 | 2 lulus | 2 lulus | Berhasil |
| `[]` | Rata-rata list kosong | 0, tidak error | 0 | Berhasil |

## Refleksi

Saya memahami bahwa list digunakan untuk menyimpan beberapa data dalam satu variabel dan indeks digunakan untuk mengakses elemen list. Saya juga memahami bahwa indeks dimulai dari 0 dan slicing dapat digunakan untuk mengambil beberapa elemen sekaligus.

Kesalahan yang berhasil saya perbaiki adalah penulisan indentasi pada blok `if` dan `for`. Saya belajar bahwa indentasi yang benar sangat penting agar program Python dapat dijalankan dengan baik.
## Kuis Formatif
Klik link di bawah ini untuk mengunduh/melihat PDF:
- [📄 Lihat File 13 Kuis Formatif (PDF)](./13%20Kuis%20Formatif.pdf)