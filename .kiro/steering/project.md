# Life Dashboard — Project Steering

## Overview
Life Dashboard adalah web app produktivitas personal yang berjalan sepenuhnya di browser.
Semua data disimpan di localStorage (client-side only), tanpa backend.

## Tech Stack
- **HTML** — struktur halaman
- **CSS** — styling (file: `css/style.css`)
- **Vanilla JavaScript** — logika app (file: `js/app.js`)
- **localStorage** — penyimpanan data

## Fitur Utama
1. **Focus Timer** — countdown timer dengan durasi custom dan suara selesai
2. **To-do List** — tambah, edit, tandai selesai, hapus tugas
3. **Quick Links** — simpan shortcut ke situs favorit
4. **Custom Nama** — personalisasi nama pengguna
5. **Dark Mode** — toggle tema terang/gelap
6. **Clock** — jam dan tanggal real-time dengan greeting otomatis

## Konvensi Kode
- Tidak menggunakan framework (no React, Vue, dll)
- Semua state disimpan ke localStorage setiap ada perubahan
- Gunakan `id` untuk elemen yang diakses JS, `class` untuk styling
- Komentar dalam Bahasa Indonesia

## Struktur File
```
index.html
css/
  style.css
js/
  app.js
```

## Non-Functional Requirements
- Load time cepat, tidak ada lag saat update UI
- Tampilan bersih dan minimal
- Kompatibel dengan Chrome, Firefox, Edge, Safari
