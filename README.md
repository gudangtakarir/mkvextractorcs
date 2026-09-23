# mkvextractorcs

# 🎬 Web gMKVExtractGUI

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Pure Client-Side](https://img.shields.io/badge/Processing-100%25%20Client--Side-green.svg)](#)
[![No Uploads](https://img.shields.io/badge/Privacy-Zero%20Data%20Uploaded-purple.svg)](#)

**Web gMKVExtractGUI** adalah implementasi web modern yang terinspirasi dari aplikasi desktop legendaris *gMKVExtractGUI*. Aplikasi ini memungkinkan Anda mengekstrak trek subtitle (`.ass`, `.srt`) dan file lampiran font (`.ttf`, `.otf`, dsb.) dari file Matroska (`.mkv`) secara massal langsung melalui browser tanpa instalasi software dan tanpa upload ke server pihak ketiga.

---

## ✨ Fitur Unggulan

- **🔒 100% Client-Side & Aman (Zero Upload):** Semua pemrosesan data dilakukan langsung di browser Anda menggunakan JavaScript Streams API. File video berukuran puluhan gigabyte pun tidak akan diunggah ke internet.
- **⚡ Probing Cepat & Hemat RAM:** Hanya membaca beberapa megabyte awal file untuk memindai metadata trek secara instan, mencegah browser mengalami crash/kehabisan memBerikut adalah draf **Deskripsi Singkat (GitHub Repository Description)** dan file **`README.md`** yang telah disesori.
- **📦 Batch Extraction ke ZIP:** Pilih beberapa file MKV sekaligus, pilih trek yang diinginkan, dan ekstuaikan dengan fitur dan arsitektur kode aplikasi Anda.

---

### 📌 GitHub Repository Description (Maks. 350 Karakter)

> **Web gMKVExtractGUI**: Alternatif gMKVExtractGUI berbasis web untuk ekstrak subtitle (ASS/SRT) & lampiran font dari file MKV langsung di browser. 100% client-side (tanpa upload ke server), hematrak semuanya dalam satu file arsip `.zip`.
- **🎯 Seleksi Cepat (Quick Select):**
  - Cent RAM via streaming reader, mendukung batch/multi-file, dan hasil otomatis dikemas dalam ZIP.

*(Panjang: 295 karakter)*

---

### 📄 `README.md`

Salin teks di bawah ini ke dalam file ang semua subtitle.
  - Centang subtitle khusus Bahasa Indonesia (`[ind]` / `[id]`).
  -`README.md`:

```markdown
# 🎬 Web gMKVExtractGUI

[![License: MIT](https://img.shields. Centang semua lampiran font.
  - Hapus semua centang dengan satu klik.
- **🖥️ Tio/badge/License-MIT-blue.svg)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Made%20with-HTML5%20%7C%20CSS3%20%7C%20ampilan Klasik TreeView:** Antarmuka tema gelap (*dark theme*) yang rapi dilengkapi Context Menu (klik kanan diJS-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Client-Side](https://img.shields.io/badge/Processing-100%25% desktop) dan kontrol dropdown ramah perangkat seluler (Android/iOS).
- **🛠️ Rekonstruksi Sub20Client--Side-brightgreen.svg)]()

**Web gMKVExtractGUI** adalah aplikasi web *title Presisi:** Memperbaiki dan menyusun ulang struktur header dan timestamp *Dialogue* format ASS (*Advanced SubStation Alpha*) serta pensingle-file* (SPA) tanpa backend yang berfungsi mengekstrak trek subtitle (`.ass` / `.srt`) sertaomoran SRT standar.

---

## 🚀 Cara Menggunakan

1. Buka file `index.html` langsung di browser modern, atau host menggunakan **GitHub Pages**.
2. Klik tombol **"📁 Tambah File MKV..."** dan pilih satu atau lebih file `.mkv`.
3. Gunakan tombol **"⚡ Seleksi Cepat"** atau centang manual trek/font yang ingin diekstrak pada TreeView.
4. Klik tombol **"🚀 Mulai Ekstrak Item Terpilih (ZIP)"**.
5. Tunggu proses streaming selesai, file ZIP akan otomatis terunduh ke lampiran font (`.ttf`, `.otf`, dll.) dari file container Matroska (`.mkv`) langsung di dalam browser.

Didesain dengan antarmuka bertema gelap ala aplikasi desktop **gMKVExtractGUI**, perangkat Anda.

---

## 🧰 Teknologi yang Digunakan

Aplikasi ini dibangun murni menggunakan Single Page Application (HTML ringan, ramah perangkat mobile (Android/iOS), dan dapat dijalankan tanpa perlu instalasi tools eksternal seperti `mkvtoolnix`.

---

## ✨ Fitur Utama

- 🔒 **100% Aman/CSS/JS) dengan memanfaatkan pustaka terbuka berikut:

- [matroska-subtitles](https:// & Client-Side**: File MKV tidak pernah diunggah ke server manapun. Seluruh proses parsing dan kompresi berlangsung di browser Anda.
- ⚡ **Scanning Cepat & Hemat RAM**: Membaca metadata file via *streaming slice* (hanya memindai beberapa MB awal untuk membaca header trek dan lampiran).
- 📦 **Ekstraksi Batch ke File ZIP**: Ekstrak beberapa file MKV sekaligus dalam sekali klik, otomatis dikemas ke arsip `.zip`.
- 🔠 **Ekstraksi Font Otomatis**: Font lampiran otomatis diekstrak dan dikelompokkan rapi ke dalam subfolder `Fonts/` di dalam ZIP.
- 🎯 **Seleksi Cepat (Quick Select)**:
  - Centang semua subtitle.
  - Centang khusus subtitle Bahasa Indonesia (`[ind]` /github.com/matiasinsaurralde/matroska-subtitles) — Parser metadata dan demuxer streaming Matroska ( `[id]`).
  - Centang semua attachment font.
  - Bersihkan semua centang.
- EBML).
- [JSZip](https://stuk.github.io/jszip/) — Generator arsip file `.zip` berbasis memori di browser.

---

## 🌐 Kompatibilitas Browser

Dibutuhkan browser modern yang mendukung `ReadableStream` dan `Blob API`:
- Google Chrome / Chromium / Brave / Edge (Desktop & Mobile)
- Mozilla Firefox (📱 **Responsif & Ramah Sentuhan**: Tersedia klik kanan (*context menu*) untuk Desktop dan dropdown praktis untuk layar sentuh / Android.
- 📝 **Rekonstruksi Format ASS Presisi**: Menyusun ulang event dan timestamp format SubDesktop & Android)
- Apple Safari (iOS 14.5+ & macOS)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah lisensi [MIT License](LICENSE).
```Station Alpha (ASS) sesuai struktur standar.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini tidak membutuhkan *build tool* (seperti Webpack, Vite, dsb.). Cukup buka file HTML langsung di peramban:

- **HTML5 & Modern CSS3** (Dark theme dengan CSS Variables)
- **Vanilla JavaScript** (ES6+ Asynchronous Streams)
- **[matroska-subtitles](https://github.com/themasch/matroska-subtitles)**: Parser Matroska berbasis stream untuk membaca struktur trek dan subs.
- **[JSZip](https://stuk.github.io/jszip/)**: Generator arsip ZIP di sisi klien.

---

## 🚀 Cara Menjalankan

### Cara 1: Langsung di Komputer Lokal
1. Unduh atau clone repositori ini:
   ```bash
   git clone https://github.com/username/web-gmkvextractgui.git
