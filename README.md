# YOMAN START — Portal Game PC, Mod Komunitas & Solusi Error

**YOMAN START** adalah platform web portal gaming & komunitas modder PC yang dikembangkan oleh **Rafli Yasin (Rafli Production)**. Dirancang dalam arsitektur Single-File Application (`index.html`) yang ringan, responsif di semua perangkat (Windows, MacBook, iPad/Tablet, Android, iPhone), serta siap di-deploy ke **GitHub Pages** maupun **Vercel** tanpa konfigurasi build tambahan.

## Fitur Utama

1. **Autentikasi Terpadu (Google Sign-In & WhatsApp OTP):**
   - **Google Sign-In:** Popup autentikasi akun Google yang bersih untuk mengambil otomatis nama lengkap dan tanggal lahir ke profil pengguna.
   - **WhatsApp OTP Notification:** Simulasi kotak notifikasi pesan masuk WhatsApp Business resmi berisi kode verifikasi 6 digit, dilanjutkan pengisian manual Nama Lengkap & Tanggal Lahir.
2. **Akses Rahasia Super Developer & Control Center (11 Fitur):**
   - Akses tersembunyi (klik 5x pada versi/logo footer atau masukkan email Super Developer) dengan proteksi permanen untuk Super Admin (`rafliyasin500@gmail.com`).
   - Dilengkapi Live Search Pengguna, Ban/Unban Reversibel (soft-hide konten), Centang Biru, Co-Developer, Pengaturan Logo & Identitas Eksklusif, Link Komunitas, Moderasi Mod & Komentar, Tambah Direktori Game + Kepatuhan Hak Cipta, Grafik Analitik Pengunjung, Monitor Sesi Realtime, Log Perangkat, Tiket Lupa Kata Sandi, dan Lonceng Notifikasi Developer.
3. **Interaksi Komunitas & Keamanan:**
   - **Fuzzy Search Global:** Pencarian pintar toleran typo (*misal: "residnt evl", "gta 5"*).
   - **Request Mod Anti-Spam:** Cooldown bertahap (`1m -> 5m -> 15m -> 60m`) dengan *live countdown timer*.
   - **Ulasan Terverifikasi Unduhan:** Rating 1–5 bintang & unggah maksimal 2 foto screenshot hanya terbuka bagi pengguna yang telah login dan mengunduh mod terkait.

## Struktur Paket Rilis

```text
yoman-start-release/
├── index.html                    # Seluruh kode HTML, CSS, & JavaScript utama
├── README.md                     # Dokumentasi proyek & panduan deploy
└── assets/
    └── yoman-start-logo.svg      # Aset vektor logo resmi YOMAN START
```

## Cara Deploy Cepat (GitHub Pages & Vercel)

### Deploy ke GitHub Pages
1. Buat repositori publik baru di GitHub (misalnya `yoman-start`).
2. Unggah seluruh isi folder hasil ekstrak (`index.html`, `README.md`, dan folder `assets/`).
3. Buka **Settings -> Pages**, pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.

### Deploy ke Vercel
1. Masuk ke [vercel.com](https://vercel.com) dan klik **Add New... -> Project**.
2. Impor repositori GitHub `yoman-start` Anda.
3. Biarkan **Framework Preset** pada `Other`, lalu klik **Deploy**. Website langsung aktif dalam ±30 detik.

---
Dikembangkan oleh **Rafli Yasin** • YOMAN START v1.0
