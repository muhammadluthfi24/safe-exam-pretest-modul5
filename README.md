<!-- README.md -->

# 🧠 Pretest Modul 5 – Regresi dengan Variabel Dummy

![Preview Ujian](https://raw.githubusercontent.com/username/pretest-modul5/main/preview.png)

Proyek ini merupakan **simulasi sistem ujian berbasis web** yang dirancang menyerupai *Safe Exam Browser*, digunakan untuk pelaksanaan **Pretest Modul 5** pada mata kuliah *Statistika Bisnis*.

Sistem ini dibangun menggunakan **HTML, CSS, dan JavaScript murni**, dengan tampilan yang modern, ringan, dan dilengkapi fitur keamanan agar peserta tidak dapat membuka tab lain atau melihat jawaban selama ujian berlangsung.

---

## 🎯 Fitur Utama

- ⏰ **Waktu terbatas**
  - Ujian hanya dapat dikerjakan pada:
    - **Tanggal:** Kamis, 30 Oktober 2025  
    - **Waktu:** Pukul **12.00–13.15 WIB**
  - Durasi pengerjaan: **20 menit**
- 🔐 **Keamanan Ujian**
  - Tidak bisa **berpindah tab** (ujian langsung berakhir)
  - Tidak bisa **klik kanan**, **tekan F12**, atau **membuka Developer Tools**
  - Tidak bisa **melihat kunci jawaban**
- 🎲 **Soal dan Opsi Diacak**
  - Setiap peserta memiliki **urutan soal dan jawaban berbeda** berdasarkan NIM
- 🧍‍♂️ **Identitas Peserta**
  - Peserta wajib mengisi **NIM dan Nama Lengkap** sebelum memulai
- 🧮 **Nilai Otomatis**
  - Nilai langsung muncul di akhir dengan format berikut:

## 💻 Teknologi yang Digunakan

| Teknologi | Deskripsi |
|------------|------------|
| **HTML5** | Struktur utama halaman ujian, termasuk form input NIM, nama, dan tampilan soal |
| **CSS3** | Menyediakan tampilan modern, responsif, dan nuansa seperti Safe Exam Browser |
| **JavaScript (Vanilla)** | Mengatur logika ujian seperti timer, pengacakan soal & opsi, anti-cheat, dan perhitungan nilai otomatis |
| **DOM API** | Manipulasi elemen HTML secara dinamis untuk menampilkan dan menyembunyikan bagian ujian |
| **Local Time Lock** | Mengunci akses berdasarkan waktu pembukaan dan penutupan ujian (30 Oktober 2025 pukul 12.00–13.15 WIB) |

---

## 📅 Jadwal Pelaksanaan Ujian

| Keterangan | Waktu |
|-------------|----------------------------|
| 📆 Dibuka | Kamis, **30 Oktober 2025 – 12.00 WIB** |
| ⏰ Ditutup | Kamis, **30 Oktober 2025 – 13.15 WIB** |
| ⏳ Durasi pengerjaan | **20 menit** |
| 📍 Lokasi pelaksanaan | Daring (Online) menggunakan browser Chrome / Edge |
| 🔐 Sistem keamanan | Otomatis menutup ujian saat keluar dari tab atau membuka fitur pengembang |

---

## 🧩 Struktur Folder

```bash
pretest-modul5/
│
├── index.html         # Halaman utama ujian (berisi HTML, CSS, dan JS)
├── README.md          # Dokumentasi lengkap proyek
├── preview.png        # Screenshot tampilan ujian (opsional)
└── assets/            # Folder untuk file pendukung (opsional)
    ├── style.css      # File CSS terpisah jika dibutuhkan
    └── script.js      # File JS terpisah jika logika ingin dipisahkan
```

## ⚠️ Catatan Penting

```bash
# ⚠️ PANDUAN SELAMA UJIAN

1. Dilarang membuka tab, jendela, atau aplikasi lain selama ujian berlangsung.
   - Sistem akan otomatis menutup ujian jika terdeteksi keluar dari tab atau membuka browser lain.
2. Dilarang menekan tombol berikut:
   - F12 (Developer Tools)
   - Ctrl + U (Lihat Sumber Halaman)
   - Ctrl + Shift + I / C (Inspect Element)
3. Dilarang melakukan klik kanan di halaman ujian.
4. Ujian hanya dapat dimulai pada waktu yang telah ditentukan:
   - Kamis, 30 Oktober 2025 pukul 12.00 WIB.
   - Berakhir pada pukul 13.15 WIB.
5. Setelah waktu habis atau peserta menekan "Submit", nilai akan langsung muncul di layar:
   - NIM, Nama, dan Nilai akan ditampilkan.
   - Muncul pesan: "Nilai Anda telah dikirim melalui link berikut: https://bit.ly/PretestModul5"
6. Gunakan browser versi terbaru (Chrome atau Edge) agar fitur keamanan berjalan dengan baik.
7. Tidak ada penyimpanan data ke server, hasil hanya tampil di sisi pengguna (client-side).
8. Disarankan menggunakan koneksi internet stabil untuk menghindari gangguan selama ujian.
```

## 🪪 Copyright & License

```bash
==========================================================
© 2025 Muhammad Luthfi Farizqi. All Rights Reserved.
==========================================================

Lisensi: MIT License

Izin diberikan kepada siapa pun untuk menggunakan, menyalin,
memodifikasi, dan mendistribusikan proyek ini untuk tujuan
akademik, pendidikan, atau pembelajaran, dengan syarat
tetap mencantumkan kredit kepada pengembang asli.

⚠️ Dilarang keras menggunakan proyek ini untuk tujuan
komersial tanpa izin tertulis dari pengembang.

Pengembang:
Nama: Muhammad Luthfi Farizqi
Institusi: Universitas Teknologi Digital Indonesia
Organisasi: Himpunan Mahasiswa Informatika (Himaforka)
Peran: Developer & Desainer Sistem Ujian
Email: luthfifarizqi23@gmail.com
GitHub: github.com/muhammadluthfi24
==========================================================
