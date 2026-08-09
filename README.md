# SAKRAL (Sistem Akuntansi Keuangan Relasi Alam & Adat) BUMMA Papua

SAKRAL adalah aplikasi pencatatan keuangan akuntansi modern yang dirancang khusus untuk **BUMMA (Badan Usaha Milik Masyarakat Adat)** di Papua. Sistem ini menyeimbangkan nilai finansial, tanggung jawab ekologis hutan adat, perlindungan hak ulayat, serta kesejahteraan komunal secara transparan dan akuntabel.

---

## 🌟 Fitur Utama

1. **Multi-Tenant BUMMA**: Isolasi data transaksi keuangan, aset biologis, dan CaLK yang aman untuk masing-masing BUMMA.
2. **Supabase Cloud Synchronization**: Sinkronisasi data real-time yang aman menggunakan arsitektur cloud serverless.
3. **Google SSO Authentication**: Memudahkan para pengelola BUMMA untuk mendaftar dan masuk secara instan menggunakan Akun Google mereka.
4. **Laporan Keuangan Adat Komprehensif**: Menghasilkan Laba Rugi, Neraca Saldo, Arus Kas, Neraca Lajur, dan Catatan atas Laporan Keuangan (CaLK) secara dinamis.
5. **Ekspor Data Mandiri**: Ekspor laporan keuangan ke format Excel (.xlsx), PDF, dan PNG, serta berbagi ringkasan via WhatsApp.
6. **Backup & Restore Mandiri**: Fitur ekspor/impor data transaksi lokal berbentuk file `.json` untuk pemindahan gadget secara mandiri oleh pengelola.
7. **Dukungan Aplikasi Android**: Dapat dipasang sebagai aplikasi Android native lengkap dengan ikon launcher segi-7 lambang wilayah adat Papua.

---

## 🛠️ Teknologi yang Digunakan

* **Frontend**: Vanilla HTML5, TailwindCSS (via CDN), vanilla JavaScript untuk performa maksimal tanpa kompilasi build yang berat.
* **Database & Auth**: Supabase JS Client (PostgreSQL, Row Level Security, Google OAuth).
* **Native Wrapper**: Ionic Capacitor untuk konversi instan ke aplikasi Android.

---

## 🚀 Cara Menjalankan Secara Lokal

1. Buka file `index.html` menggunakan peramban browser Anda.
2. Untuk mensimulasikan lingkungan server lokal (dukungan PWA penuh), jalankan perintah berikut di terminal folder proyek Anda:
   ```bash
   python -m http.server 8000
   ```
   Lalu buka peramban di alamat `http://localhost:8000`.

---

## 📱 Cara Kompilasi Aplikasi Android (.apk)

1. Buka **Android Studio**.
2. Pilih **Open an Existing Project**, arahkan ke folder sub-proyek:  
   `d:\8 PROJECT\2026\sakral\android`
3. Pastikan **Gradle JDK** diatur ke versi **`jbr-21`** (Java 21) di menu *Settings > Build, Execution, Deployment > Build Tools > Gradle*.
4. Klik menu **Build** > **Generate App Bundles or APKs** > **Generate APKs**.
5. Ambil file `app-debug.apk` hasil kompilasi, rename, dan siap dibagikan!

---

*“Menyeimbangkan nilai finansial, tanggung jawab ekologis hutan adat, perlindungan ulayat, serta kesejahteraan bersama secara transparan di bawah naungan 7 Wilayah Adat Papua.”*

**SAKRAL BUMMA Papua** © 2026. Dikembangkan bekerja sama dengan **Fakultas Ekonomi dan Bisnis (FEB) Universitas Cenderawasih (UNCEN)** untuk keberlanjutan dan kemandirian ekonomi masyarakat adat Papua.
