# 🎬 Web gMKVExtractGUI

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Language-Vanilla%20JS-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Client-Side Processing](https://img.shields.io/badge/Processing-100%25%20Client--Side-brightgreen.svg)](#)
[![Privacy First](https://img.shields.io/badge/Privacy-No%20Uploads-purple.svg)](#)

Aplikasi web modern berbasis *single-file* (SPA) tanpa backend yang terinspirasi dari tool desktop **gMKVExtractGUI**. Aplikasi ini memungkinkan Anda mengekstrak trek subtitle (`.ass`, `.srt`) dan file lampiran font (`.ttf`, `.otf`, dll.) dari file container Matroska (`.mkv`) secara massal langsung melalui peramban web (browser).

Tidak perlu instalasi aplikasi tambahan atau dependensi binary `mkvtoolnix`.

---

## ✨ Fitur Utama

- 🔒 **100% Client-Side & Privasi Terjaga:** File video berukuran besar sekalipun tidak pernah diunggah ke server manapun. Seluruh proses parsing dan pembuatan ZIP dilakukan langsung di dalam browser Anda.
- ⚡ **Scanning Cepat & Hemat RAM:** Menggunakan metode *streaming chunks*. Hanya membaca ~5 MB awal untuk memindai susunan trek dan header, mencegah peramban kehabisan memori.
- 📦 **Ekstraksi Batch ke File ZIP:** Mendukung banyak file MKV sekaligus dalam sekali proses antrean dan otomatis diunduh dalam arsip `.zip`.
- 🔠 **Organisasi Font Otomatis:** Lampiran font yang diekstrak otomatis dikelompokkan ke dalam subfolder `Fonts/` di dalam ZIP.
- 🎯 **Seleksi Cepat (Quick Select):**
  - Centang semua subtitle.
  - Centang subtitle Bahasa Indonesia saja (`[ind]` / `[id]`).
  - Centang semua lampiran font.
  - Bersihkan semua centang.
- 🖥️ **Antarmuka Klasik TreeView:** Dilengkapi tema gelap (*dark theme*) yang bersih, klik kanan (*context menu*) untuk desktop, serta tombol dropdown praktis untuk layar sentuh / Android.
- 📝 **Rekonstruksi Format ASS Presisi:** Menyusun ulang header script, *styles*, serta format event dialog dan timestamp ASS (*Advanced SubStation Alpha*) secara akurat.

---

## 🚀 Cara Menjalankan

### Opsi 1: Buka Secara Lokal
1. Unduh atau clone repositori ini:
   ```bash
   git clone https://github.com/username/web-gmkvextractgui.git
