# Membangun Family Movie Watchlist API

[![GitHub Pages](https://img.shields.io/badge/BACA_EBOOK-SEKARANG-brightgreen?style=for-the-badge&logo=github)](https://kartonobinsaleh.github.io/ebook-family-watchlist-api/)

Selamat datang di repositori **Membangun Family Movie Watchlist API**. Ini adalah sebuah panduan interaktif (eBook) yang membahas langkah demi langkah pembuatan REST API menggunakan Node.js, Express, bcrypt, dan JWT. 

Materi ini disusun untuk mempermudah penyelesaian proyek dari kurikulum **FreeCodeCamp: Back End Development and APIs**, namun dengan pendekatan _"pahami dulu konsepnya, baru tulis kodenya"_.

---

## 📖 Baca eBook

eBook ini telah di-deploy menggunakan GitHub Pages. Kamu bisa langsung membacanya melalui tautan berikut:

👉 **[Baca Membangun Family Movie Watchlist API](https://kartonobinsaleh.github.io/ebook-family-watchlist-api/)**

---

## 🚀 Apa yang Akan Kamu Pelajari?

Di dalam eBook ini, kita akan membangun fitur lapis demi lapis:

- **Bab 1: Mengenal REST API dan Setup Project**
  - Pemahaman dasar arsitektur REST.
  - Setup Express, instalasi `helmet`, `bcryptjs`, dan `jsonwebtoken`.
- **Bab 2: CRUD Watchlist**
  - Pemetaan logika bisnis (Create, Read, Update, Delete).
  - Simulasi database menggunakan file statis (`.json`).
- **Bab 3: Keamanan Password dengan bcrypt**
  - Bahaya menyimpan *plaintext password*.
  - Konsep *hashing*, *salting*, dan mengapa algoritma yang lambat (bcrypt) justru lebih baik.
- **Bab 4: Autentikasi dengan JWT**
  - Memecahkan masalah HTTP yang *stateless*.
  - Anatomi JSON Web Token (Header, Payload, Signature).
  - Pembuatan middleware `authenticate`.
- **Bab 5: Otorisasi (RBAC)**
  - Perbedaan mendasar antara Autentikasi vs Otorisasi.
  - Role-Based Access Control (Hak akses antara *parent* vs *child*).
  - Pembuatan middleware `authorizeModification`.

---

## 🛠️ Stack Teknologi

- **Node.js**
- **Express 5.x** — *Web framework*
- **bcryptjs** — *Hashing password*
- **jsonwebtoken** — *Autentikasi*
- **helmet** — *Security headers*

---
