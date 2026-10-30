## 7. Algoritma dan Pseudocode
MULAI
baca data dari file
jika file tidak ditemukan:
    tampilkan pesan error
    SELESAI
untuk setiap baris data:
    validasi format dan nilai
    simpan data valid
hitung statistik
tentukan status ketuntasan
tampilkan ringkasan
simpan laporan
SELESAI

## 8. Struktur Program dan Modularisasi
- `main.py`: Mengatur alur utama program.
- `src/input_data.py`: Membaca file data.
- `src/analisis.py`: Validasi nilai, hitung statistik, dan status kelulusan.

## 9. Struktur Data
Menggunakan **List** untuk urutan nilai dan **Dictionary** untuk ringkasan statistik.

## 10. Test Case
- TC01 (Normal): Nilai 70, 80, 90 -> Rata-rata 80.
- TC02 (Batas): Nilai 0 -> Diterima sebagai nilai valid.
- TC03 (Batas): Nilai 100 -> Diterima sebagai nilai valid.
- TC04 (Invalid): Nilai 105 -> Ditolak dengan pesan validasi.
- TC05 (Invalid): File tidak ada -> FileNotFoundError ditangani.

## 11. Pembagian Tugas
- Koordinator: Menjaga ruang lingkup dan integrasi.
- Programmer I/O: Mengelola pembacaan file (`input_data.py`).
- Programmer Logika: Mengelola fungsi statistik (`analisis.py`).
- Tester / QA: Menyusun dan menjalankan test case.
- Dokumentasi: Menyusun README.md.

## 12. Jadwal (Milestone)
- Pertemuan 14: Proposal, struktur repositori, pseudocode, dan test case.
- Pertemuan 15: Implementasi, testing, debugging, dan dokumentasi.
- Pertemuan 16: Presentasi dan evaluasi akhir.

## 13. Repositori GitHub
URL: https://github.com/ahadinilman/Pertemuan-14.git
