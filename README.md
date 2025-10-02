# Golden Dragon Wok — Demo Modul 1

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Proyek statis: situs multi-halaman (Beranda, Menu, Tentang, Kontak) untuk restoran fiktif "Golden Dragon Wok".

Ini dibuat sebagai tugas/demonstrasi untuk:

- Mata kuliah: Pemrograman Web
- Semester: 5
- Program studi: Teknik Informatika, Universitas Muhammadiyah Malang (UMM)
- NIM: 202310370311437
- Nama: WIJI FIKO TEREN

Deskripsi singkat
------------------
Situs ini adalah contoh statis yang menggunakan HTML5, Tailwind CSS (via CDN) dan beberapa CSS kustom di `assets/styles.css`. Layout responsif, navigasi konsisten antar halaman, dan gambar menu serta hero disediakan secara lokal di folder `assets/`.

Struktur singkat proyek
----------------------

- `index.html` — Beranda (hero, CTA, preview menu)
- `menu.html` — Halaman daftar menu dengan foto, deskripsi, dan harga
- `about.html` — Tentang restoran & profil pemilik
- `contact.html` — Kontak + peta (OpenStreetMap) + formulir contoh
- `assets/` — Semua gambar (hero, foto menu), logo, dan `styles.css`

Menjalankan secara lokal
------------------------

Cara tercepat untuk melihat situs di mesin Anda (dari folder proyek):

```bash
# masuk ke folder proyek
cd "/Users/fiko/Downloads/Pemrograman Web/Modul 1/landing page"

# jalankan server HTTP sederhana (Python 3)
python3 -m http.server 8000

# buka browser dan akses:
http://localhost:8000/index.html
```

Catatan
------
- Gambar menu dan hero sudah ditempatkan di `assets/` untuk penggunaan offline.
- Formulir pada halaman `contact.html` adalah contoh statis (tidak mengirim email). Hubungkan backend atau layanan form jika ingin menyimpan/menerima pesan nyata.
- Tailwind digunakan via CDN untuk kemudahan demo. Untuk produksi, pertimbangkan build step Tailwind untuk mengurangi ukuran CSS.

Kontak pembuat
---------------
- Nama: WIJI FIKO TEREN
- Email (tercantum di halaman): tobellord@gmail.com

Lisensi
-------
Proyek ini dibuat untuk keperluan demo/tugas pendidikan. Gunakan sesuai kebijakan pengajar.
