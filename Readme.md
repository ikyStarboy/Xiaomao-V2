<img src="https://raw.githubusercontent.com/Ryuikyyz/Api-imgbb/refs/heads/main/umaS3/Tak%20berjudul65_20260110002358.png" alt="banner">
<h1 align="center"><img src="https://raw.githubusercontent.com/Ryuikyyz/Api-imgbb/refs/heads/main/umaS3/Tak%20berjudul66_20260110002932.png" width="22px"> Xiaomao V2 - Chatbot Telegram & discord</h1>

<p align="center">
	<a href="https://nodejs.org/dist/v16.20.0">
		<img src="https://img.shields.io/badge/Nodejs%20Support-16.x-brightgreen.svg?style=flat-square" alt="Nodejs Support v16.x">
	</a>
  <img alt="size" src="https://img.shields.io/github/repo-size/Ryuikyyz/Xiaomao-V2.svg?style=flat-square&label=size">
  <img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=brightgreen&label=code%20version&prefix=v&query=%24.version&url=https://github.com/Ryuikyyz/Xiaomao-V2/raw/main/package.json&style=flat-square">
  <img alt="visitors" src="https://visitor-badge.laobi.icu/badge?style=flat-square&page_id=Ryuikyyz.Xiaomao-V2">
  <img alt="size" src="https://img.shields.io/badge/license-MIT-green?style=flat-square&color=brightgreen">
</p>

- [📝 **Note**](#-note)
- [🔔 **Main Feature**](#-main-feature)
- [🆙 **How to Update**](#-how-to-update)
- [🛠️ **Requirements**](#️-preparation-before-install)
- [💭 **Support**](#-support)
- [📚 **How To Install**](#-how-to-install)
- [📸 **Recommendation Hosting**](#-recommendation-hosting)
- [✨ **Contributor**](#-contributor)
- [📜 **License**](#-license)

<hr>

## ☕ **Note**
Xiaomao-V2 adalah bot hybrid modern yang berjalan di dua platform sekaligus: **Telegram** dan **Discord**. Dibangun dengan Node.js untuk memberikan pengalaman manajemen bot yang ringan, cepat, dan stabil.

---

## 🚀 **Main Feature**

* **Dual Platform**: Aktif di Telegram dan Discord hanya dengan satu kali run.
* **Adaptive Menu**:
    * **Telegram**: Sistem halaman (pagination) dengan tombol navigasi.
    * **Discord**: Tampilan profesional menggunakan ANSI Code Block agar rapi dan berwarna.
* **Smart Role System**: Proteksi akses command berdasarkan Owner, Admin Grup/Server, atau User Umum.
* **Dynamic Command Manager**:
    * install: Tambah/update fitur langsung dari chat tanpa matiin bot.
    * del: Hapus fitur yang tidak diinginkan lewat chat.
    * list: Cek semua file command yang terpasang.
* **Hybrid Callad**: Fitur laporan user/panggilan admin yang bisa saling balas antar platform.
* **Auto Restart**: Bot otomatis hidup kembali jika terjadi error atau crash (menggunakan run.sh).

---

## 🛠️ **Preparation Before Install**

Pastikan kamu sudah menyiapkan:

1. **Node.js v16+**: Wajib terinstall.
2. **Bot Token Telegram**: Ambil di [@BotFather](https://t.me/BotFather).
3. **Bot Token Discord**: Ambil di [Discord Developer Portal](https://discord.com/developers/applications).
    * PENTING: Di bagian Bot, aktifkan semua Privileged Gateway Intents (Presence, Server Members, Message Content).
4. **Admin ID**: Ambil ID akun kamu di Telegram dan Discord untuk akses Owner.

## 💭 **Support**

Punya Keluhan, Gk ngerti awalan, atau ketemu bug? Klik tombol di bawah ini:

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/rngVV3WCp)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/groups/350004878030834/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6281318293478)
[![Telegram](https://img.shields.io/badge/Telegram-26A6E6?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/KyysStoreID)

> [!CAUTION]
> **PENTING**: Tolong jangan hubungi via inbox pribadi. Gunakan link grup di atas agar pesan Anda terbaca.

---

## 📦 **How to install**

### 1. Clone Repository
```bash 
git clone https://github.com/ikyStarboy/Xiaomao-V2
```

### 2. Masuk ke direktori
```bash
 cd Xiaomao-V2
 ```

### 3. Install Dependencies
```bash
npm install
```

### 4. Konfigurasi Bot
Edit file settings.js:
```bash
module.exports = {
    botToken: "TOKEN_TELE_MU",
    TokenDc: "TOKEN_DISCORD_MU",
    adminID: ["ID_USER_TELE_MU"],
    adminDc: ["ID_USER_DISCORD_MU"],
    botName: "Xiaomao Bot",
    OwnerTg: "t.me/KyysStoreID",
    prefix: "-",
    isMaintenance: false
};
```

### 5. Berikan Izin Script Shell
```bash 
chmod +x run.sh
```
### 6. Jalankan Bot
```bash 
npm start
```
---

## 🌐 **Recommendation Hosting**

Untuk menjaga bot tetap online 24/7, gunakan layanan berikut:
* VPS (Ubuntu/Debian): Rekomendasi utama (Gunakan pm2 atau screen).
* Panel Pterodactyl: Sangat mudah digunakan untuk manajemen bot.
* [Termux](https://f-droid.org/repo/com.termux_1022.apk): Bisa digunakan di Android (Gunakan tsu agar bot tidak mati saat HP standby).

---

## 👨‍💻 **Contributor**

* [ikyStarboy](https://github.com/ikyStarboy) - GitHub
* [Gemini Ai](gemini.google.com) - Assistant Developer

---

## 📜 **License**

* Projek ini bersifat Open Source.
* Dilarang keras memperjualbelikan script ini tanpa izin.
* Gunakan dengan bijak dan jangan melanggar TOS Telegram/Discord.

**Copyright © 2026 iky x gemini**