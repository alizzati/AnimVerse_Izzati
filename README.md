# Anime Verse

![App Logo](assets/images/app_icon.png)

**Anime Verse** adalah aplikasi mobile berbasis Flutter yang dikembangkan sebagai Final Project Praktikum Pemrograman Mobile 2025. Aplikasi ini memungkinkan pengguna untuk menjelajahi ribuan koleksi anime, mencari judul spesifik, memfilter berdasarkan genre, serta menyimpan anime favorit mereka ke dalam database cloud yang aman.

Aplikasi ini terintegrasi dengan **Jikan API (MyAnimeList)** untuk data anime dan **Firebase** untuk autentikasi serta penyimpanan data pengguna.

---

## 👨‍🎓 Identitas Mahasiswa
**Tugas Besar Pemrograman Mobile - IKLC USU**

| Nama | Nur Aliza Izzati |
| :--- | :--- |
| **NIM** | 231401076 |
| **Kom** | A |
| **Lab** | 2 |
| **Asisten Lab** | Rivaldo Dominggos Pardede |

---

## 📥 Download & Demo

- **📱 Download APK (v1.0.0):** [Klik disini untuk Download APK](https://github.com/alizzati/AnimVerse_Izzati/releases/tag/v1.0.0)
- **🎥 Video Demo:** [Tempel Link YouTube/Google Drive Disini]

---

## ✨ Fitur Utama

### 1. Autentikasi (Firebase Auth)
- **Sign Up & Sign In:** Login aman menggunakan Email & Password.
- **Google Sign-In:** Login cepat menggunakan akun Google (SSO).
- **Forgot Password:** Fitur reset kata sandi via email.
- **Auto Login:** Menyimpan sesi pengguna (Persistensi).

### 2. Anime Discovery (API Integration)
- **Browse Anime:** Menampilkan daftar anime populer dengan sistem *Pagination* (Load More) agar aplikasi ringan.
- **Search:** Pencarian anime berdasarkan judul secara real-time.
- **Filter Genre:** Menyaring anime berdasarkan kategori (Action, Romance, Fantasy, dll).

### 3. Favorit (Cloud Firestore)
- **Add to Favorite:** Menyimpan anime ke daftar pribadi.
- **Real-time Database:** Data tersimpan di Cloud Firestore dengan *Security Rules* (User-Scoped), memastikan data aman dan terpisah antar pengguna.
- **Remove Favorite:** Menghapus anime dari daftar favorit.

### 4. Manajemen Profil
- Change Password.
- Logout.

---

## 📸 Screenshots Aplikasi

| Login & Register | Home Page | Search & Filter |
| :---: | :---: | :---: |
| ![Login](screenshots/login.png) | ![Home](screenshots/home.png) | ![Search](screenshots/search.png) |
| *Halaman Login* | *Halaman Utama* | *Pencarian & Filter* |

| Detail Anime | My Favorites | Profile |
| :---: | :---: | :---: |
| ![Detail](screenshots/detail.png) | ![Favorites](screenshots/favorites.png) | ![Profile](screenshots/profile.png) |
| *Detail Info* | *List Favorit* | *Profil User* |

*(Catatan: Screenshot diambil dari perangkat Redmi Note 8)*

---

## 🛠️ Teknologi yang Digunakan

- **Framework:** Flutter (Dart)
- **Backend:** Firebase (Authentication, Cloud Firestore)
- **API:** Jikan API v4 (Unofficial MyAnimeList API)
- **State Management:** Provider
- **Local Storage:** Shared Preferences (untuk caching token/tema)

---

## 🏗️ Cara Instalasi (Untuk Developer)

Jika Anda ingin menjalankan source code ini di komputer lokal:

1. **Clone Repository**
   ```bash
   git clone [https://github.com/](https://github.com/)[USERNAME_GITHUB_ANDA]/anime_verse.git
