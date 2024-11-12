
# Gaea - Multi-Mode Mining Bot

**Gaea** adalah bot mining otomatis dengan dukungan untuk penggunaan lokal (IP VPS) dan proxy, serta fitur refresh otomatis saat skor jaringan di bawah batas tertentu.

Link:https://app.aigaea.net/register?ref=gaEUpZ0kxAlWiG

## 📋 Fitur
- **Mining Local**: Melakukan mining menggunakan IP lokal atau VPS.
- **Mining Proxy**: Mendukung mining melalui proxy.
- **Auto Refresh**: Memuat ulang otomatis jika skor jaringan di bawah 50, memastikan koneksi tetap optimal.
- **Auto Checkin Daily**: Otomatis melakukan checkin setiap hari.

## 🚀 Instalasi
1. **Instal Dependencies**:
   - Pastikan Node.js dan npm sudah terinstal di sistem Anda.
   - Jalankan perintah berikut untuk menginstal dependencies yang diperlukan:
     ```bash
     npm install axios uuid fake-useragent
     ```

2. **Dapatkan Bearer Token**:
   - Buka aplikasi web yang ingin digunakan bersama **Gaea**.
   - Tekan `F12` untuk membuka Developer Tools, lalu tekan gambar console.
   - Paste code ini di console:
   ```bash
   const browserId = localStorage.getItem("browser_id").substring(0, 8);
   const gaeaToken = localStorage.getItem("gaea_token");
   const data = `{"browser_id": "${browserId}", "gaea_token": "${gaeaToken}"}`;
   copy(data);
   console.log("Data copied to clipboard:", data);
   ```
   - Paste hasil auto copy kedalam dalam file accounts.txt
     
   ![Screenshot 2024-11-12 230333](https://github.com/user-attachments/assets/3f8c3cba-bf61-4fd8-b27c-a621daf2c1e7)
   


   

4. **Dapatkan Proxy Gratis**:
   - Untuk menggunakan proxy gratis, Anda bisa mengunjungi [Webshare.io](https://www.webshare.io/?referral_code=nppjfy3iuura) dan klaim 10 proxy premium gratis.

## ⚠️ Catatan
- **Auth Menggunakan Token**: Karena autentikasi bot ini menggunakan token, dan saat ini belum ada metode auto-refresh token, silakan sering cek token secara manual jika mengalami error pada script.
- **Resiko Penggunaan**: Penggunaan script ini sepenuhnya menjadi tanggung jawab pengguna. Harap gunakan dengan bijak.

## 🤝 Apresiasi
Jika script ini membantu, dukung author dengan mengikuti akun ini agar author bisa membangun portofolio untuk proyek di masa mendatang!
