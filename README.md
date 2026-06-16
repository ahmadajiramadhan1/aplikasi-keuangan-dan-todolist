# Campuran App

Dashboard pribadi untuk produktivitas dan catatan keuangan harian.

## Fitur

- Kunci keamanan dengan password, pertanyaan rahasia, master key, dan Google Authenticator.
- Jam digital WIB dengan fallback offline.
- Catatan pemasukan dan pengeluaran per tanggal.
- Rekening/dana dengan saldo awal.
- Transfer antar rekening.
- Kategori pemasukan dan pengeluaran yang bisa ditambah.
- Manajemen tugas harian, tugas rutin, progress, dan riwayat selesai.
- Backup dan tarik data cloud melalui endpoint Google Apps Script.

## Cara Menjalankan

Buka `index.html` langsung di browser.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload semua file di folder ini ke repository.
3. Buka `Settings` > `Pages`.
4. Pada `Build and deployment`, pilih `Deploy from a branch`.
5. Pilih branch `main` dan folder `/root`.
6. Simpan, lalu tunggu link GitHub Pages muncul.

## Catatan Data

Aplikasi menyimpan data utama di `localStorage` browser. Data akan mengikuti browser/perangkat yang dipakai, kecuali kamu memakai fitur backup cloud di dalam aplikasi.
