<div align="center">
  <img src="https://telegra.ph/file/84df002d242cb66bbdb25.jpg" alt="Banner" width="100%" style="border-radius: 15px;">
  
  <br><br>

  # 🤖 Bot Auto Order Telegram + 📱 Web Mini App
  **Sistem Toko Digital Otomatis via Telegram dengan Integrasi QRIS & Dashboard Mini App**

  <p align="center">
    <a href="#"><img src="https://img.shields.io/badge/Node.js-v16+-green?style=for-the-badge&logo=node.js"></a>
    <a href="#"><img src="https://img.shields.io/badge/Telegraf-Framework-blue?style=for-the-badge&logo=telegram"></a>
    <a href="#"><img src="https://img.shields.io/badge/Payment-QRIS_Auto-orange?style=for-the-badge"></a>
    <a href="#"><img src="https://img.shields.io/badge/UI-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss"></a>
  </p>
</div>

---

## ✨ Fitur Utama

### 🛠️ Fitur Bot (Backend)
- **🛍️ Katalog Otomatis:** Sistem membaca produk dan stok secara realtime.
- **💳 Payment Gateway:** Mendukung pembayaran QRIS Otomatis (MustikaPay & Artan Shop) serta Saldo User.
- **📦 Auto-Kirim Produk:** Bot otomatis mengirimkan detail akun/produk setelah pembayaran sukses.
- **👑 Panel Admin In-App:** Kelola produk, tambah/hapus stok, ubah harga, dan broadcast langsung dari chat Telegram!
- **💾 Database Ringan:** Menggunakan sistem JSON lokal (tanpa perlu setup MySQL/MongoDB).
- **🛡️ Backup System:** Admin dapat mendownload backup database dan script langsung dari bot.

### 📱 Fitur Mini App (Frontend)
- **🪞 UI/UX Premium:** Desain modern *Dark Mode* dengan efek *Glassmorphism*.
- **🆔 Digital Identity Card:** Membaca data pengguna Telegram (Nama, UID) secara realtime untuk kemudahan komplain/top-up.
- **✨ Premium Badge:** Mendeteksi otomatis jika user menggunakan Telegram Premium.
- **📚 Pusat Bantuan Terpusat:** Tutorial order, Syarat & Ketentuan, dan tombol *Direct Contact* ke Admin.

---

## 📋 Persyaratan Sistem
Sebelum menjalankan script ini, pastikan Anda memiliki:
1. **Node.js** (Versi 16 atau lebih baru).
2. **Bot Token** dari [@BotFather](https://t.me/BotFather).
3. Akun/API Key dari **MustikaPay** atau **Artan Shop** (jika ingin QRIS otomatis).
4. VPS, Panel Pterodactyl, atau layanan hosting (seperti Vercel untuk Mini App).

---

## 🚀 Cara Instalasi & Menjalankan Bot

### 1. Clone & Install Dependencies
Buka terminal Anda dan jalankan perintah berikut:
```bash
# Clone repositori (jika pakai git)
git clone [https://github.com/username-kamu/repo-bot.git](https://github.com/username-kamu/repo-bot.git)
cd repo-bot

# Install modul NPM yang dibutuhkan
npm install telegraf fs-extra uuid axios adm-zip express cors
