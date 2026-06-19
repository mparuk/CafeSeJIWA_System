# ☕ Cafe SeJIWA System

![Status: Selesai](https://img.shields.io/badge/Status-Selesai-success?style=flat-square)
![Language: C](https://img.shields.io/badge/Language-C-blue?style=flat-square)
![Data Structure: Max-Heap](https://img.shields.io/badge/Data%20Structure-Max--Heap-orange?style=flat-square)

**Cafe SeJIWA System** adalah aplikasi perangkat lunak berbasis *Command Line Interface* (CLI) yang dirancang khusus untuk mengoptimalkan manajemen operasional harian di Cafe SeJIWA. Dibangun menggunakan bahasa pemrograman **C**, sistem ini mengimplementasikan struktur data **Max-Heap** untuk mengelola antrean dan prioritas pesanan secara dinamis, memastikan pelayanan yang lebih cepat, efisien, dan terstruktur.

---

## ✨ Fitur Utama

- **Manajemen Antrean Prioritas (Max-Heap):** Mengelola daftar pesanan secara otomatis berdasarkan tingkat prioritas (misalnya: pelanggan VIP atau pesanan *express* akan diproses terlebih dahulu).
- **Pencatatan Operasional Cepat:** Meminimalkan waktu input dan output data pesanan pelanggan untuk menghindari penumpukan antrean.
- **Efisiensi Memori & Eksekusi:** Algoritma yang ringan dan dioptimalkan menggunakan bahasa C untuk menjamin program berjalan dengan performa tinggi tanpa jeda.

## 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:
1. Meningkatkan *Service Level Agreement* (SLA) pelayanan di Cafe SeJIWA.
2. Memberikan solusi komputasi yang efisien untuk mengatasi antrean panjang di jam-jam sibuk (*rush hour*).
3. Mengaplikasikan teori struktur data non-linear (Heap) ke dalam solusi bisnis dunia nyata.

---

## 🛠️ Teknologi & Perangkat

- **Bahasa Pemrograman:** C
- **Struktur Data Inti:** Max-Heap
- **Lingkungan Eksekusi:** Terminal / Command Prompt (CLI)
- **Kompilator yang Didukung:** GCC, Clang, atau MinGW

---

## 🚀 Cara Instalasi & Penggunaan

Untuk menjalankan sistem ini di komputer Anda, pastikan Anda telah menginstal *compiler* bahasa C (seperti GCC).

**1. Clone repositori ini:**
```bash
git clone https://github.com/mparuk/CafeSeJIWA_System.git
cd CafeSeJIWA_System
```

**2. Kompilasi program:**
```bash
gcc -o cafe cafe.c
```

**3. Jalankan program:**
- **Windows:**
  ```bash
  cafe.exe
  ```
- **Linux / macOS:**
  ```bash
  ./cafe
  ```
*(Catatan: Pastikan file `menu.txt` berada di dalam direktori yang sama saat program dijalankan agar sistem dapat memuat data menu dengan benar).*

---

## 👥 Tim Pengembang

Sistem ini dirancang dan dikembangkan secara kolaboratif oleh tim mahasiswa yang berdedikasi:

| Nama | Peran / Kontribusi | Profil GitHub |
| :--- | :--- | :--- |
| **Muhammad Paruk** | Pengembang Inti | [@mparuk](https://github.com/mparuk) |
| **Adriel Hagai Brenta Meliala** | Pengembang Inti | [@Adrielmeliala](https://github.com/Adrielmeliala) |
| **Muhammad Febriyan** | Pengembang Inti | [-] |

---

## 📌 Status Proyek

✔️ **Selesai (Completed)**

Sistem ini telah melewati tahap pengembangan inti, pengujian awal, serta siap diimplementasikan untuk operasional. Kami berterima kasih atas seluruh dukungan, masukan, dan evaluasi yang telah diberikan oleh berbagai pihak selama masa perancangan hingga penyelesaian proyek ini.
