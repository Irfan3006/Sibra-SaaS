# Sibra SaaS - Ecosystem Platform

[**Sibra SaaS**](https://saas.sibra.store) adalah platform ekosistem modern yang menyediakan berbagai tools dan solusi digital siap pakai untuk UMKM, mahasiswa, dan teknisi digital. Platform ini dirancang dengan antarmuka yang bersih, cepat, dan sepenuhnya responsif, mengutamakan privasi pengguna dengan pemrosesan data di sisi klien (Client-Side).

## Main Products

### 1. [QR Code Generator](https://saas.sibra.store/qr-code-generator/)
- Generator QR Code gratis tanpa login.
- Support **Logo di tengah** untuk branding profesional.
- Mendukung tipe data: **URL, Teks Bebas, dan WhatsApp Chat**.
- Fitur **Donasi QRIS** terintegrasi.
- Optimasi SEO (JSON-LD & WebApplication) untuk pasar Indonesia.

### 2. [QR Code Reader / Scanner](https://saas.sibra.store/qr-code-reader/)
- Pembaca QR Code online tercepat menggunakan kamera smartphone atau laptop.
- Support **Upload Gambar** dari galeri (JPG, PNG, WebP).
- Keamanan Privasi: Pemrosesan decoding dilakukan 100% di browser Anda (Local Decoding).
- UI/UX ringan dan mobile-optimized.

### 3. [Image Compressor & Converter](https://saas.sibra.store/converter-image/)
- Kompresi gambar batch (hingga 20 file sekaligus).
- Konversi format populer: **JPG, PNG, WebP, dan HEIC (iPhone)**.
- **Smart Presets**: High, Medium, Low, dan Web Optimized.
- Arsitektur Performa: Menggunakan **Web Workers (OffscreenCanvas)** agar UI tidak freeze saat memproses file besar.
- Statistik Efisiensi: Total MB saved, efisiensi %, dan waktu proses.

## Key Features & Architecture

- **Zero-Upload Policy**: Semua pemrosesan (QR generation, Image compression, QR Decoding) dilakukan di sisi klien. Kami tidak mengirimkan data atau gambar Anda ke server kami.
- **Web Worker Engine**: Image processing berjalan di background thread, menjamin pengalaman mulus bahkan pada perangkat low-end.
- **Memory Management**: Sistem `ObjectURL Registry` otomatis untuk mencegah memory leak selama sesi penggunaan panjang.
- **SEO Ready**: Terintegrasi dengan Meta Tags lengkap, Canonical Tags, dan JSON-LD Structured Data (`WebApplication`, `FAQPage`).

## Tech Stack

- **HTML5 & Vanilla JavaScript (ES6+)**: Menjamin performa super cepat tanpa overhead framework.
- **Tailwind CSS**: Desain modern, elegan, dan profesional (UI/UX fokus).
- **Html5-QRCode**: Library scanner QR dengan deteksi real-time tercepat.
- **heic2any**: Mendukung konversi format Apple HEIC secara lokal.
- **JSZip**: Menangani pengarsipan bulk download menjadi satu file ZIP secara instan.

## Project Structure

- `index.html`: Landing page utama Sibra SaaS.
- `qr-code-generator/`: Folder aplikasi QR Code Generator.
- `qr-code-reader/`: Folder aplikasi QR Code Reader.
- `converter-image/`: Folder aplikasi Image Compressor & Converter.
- `assets/`: Folder untuk gambar, favicon, dan resource statis lainnya.
- `favicon.webp`: Favicon platform yang konsisten.

## Licenses & Copyrights

Open Source **MIT License**. © 2026 Sibra Tech Company. All rights reserved.

---
*Dibuat dengan ❤️ oleh [Irfan Syarifudin](https://irfan-syarifudin.vercel.app/) untuk kemajuan digital Indonesia.*