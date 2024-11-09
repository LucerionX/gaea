
# Gaea - Multi-Mode Mining Bot

**Gaea** adalah bot mining otomatis dengan dukungan untuk penggunaan lokal (IP VPS) dan proxy, serta fitur refresh otomatis saat skor jaringan di bawah batas tertentu.

## 📋 Fitur
- **Mining Local**: Melakukan mining menggunakan IP lokal atau VPS.
- **Mining Proxy**: Mendukung mining melalui proxy.
- **Auto Refresh**: Memuat ulang otomatis jika skor jaringan di bawah 50, memastikan koneksi tetap optimal.

## 🚀 Instalasi
1. **Instal Dependencies**:
   - Pastikan Node.js dan npm sudah terinstal di sistem Anda.
   - Jalankan perintah berikut untuk menginstal dependencies yang diperlukan:
     ```bash
     npm install axios uuid fake-useragent
     ```

2. **Dapatkan Bearer Token**:
   - Buka aplikasi web yang ingin digunakan bersama **Gaea**.
   - Tekan `F12` untuk membuka Developer Tools, lalu tekan `Ctrl + R` untuk reload.
   - Buka tab **Network** dan cari request dengan nama `session`.
   - Gulir untuk menemukan token Bearer, yang akan terlihat seperti `Bearer eyxxxx`.

3. **Dapatkan Proxy Gratis**:
   - Untuk menggunakan proxy gratis, Anda bisa mengunjungi [Webshare.io](https://www.webshare.io/?referral_code=nppjfy3iuura) dan klaim 10 proxy premium gratis.

## ⚠️ Catatan
- **Auth Menggunakan Token**: Karena autentikasi bot ini menggunakan token, dan saat ini belum ada metode auto-refresh token, silakan sering cek token secara manual jika mengalami error pada script.
- **Resiko Penggunaan**: Penggunaan script ini sepenuhnya menjadi tanggung jawab pengguna. Harap gunakan dengan bijak.

## 🤝 Apresiasi
Jika script ini membantu, dukung author dengan mengikuti akun ini agar author bisa membangun portofolio untuk proyek di masa mendatang!
