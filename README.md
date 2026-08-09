# SAKRAL (Sistem Akuntansi Keuangan Relasi Alam & Adat) BUMMA Papua

SAKRAL adalah aplikasi pembukuan dan akuntansi modern yang dirancang khusus untuk mendukung **BUMMA (Badan Usaha Milik Masyarakat Adat)** di tanah Papua. Aplikasi ini menjembatani pencatatan transaksi finansial komersial dengan tanggung jawab pelestarian hutan adat, perlindungan hak ulayat, serta kontribusi sosial bagi kesejahteraan komunal.

---

## 🌟 Keunggulan & Fitur Utama

* **🌿 Integrasi Nilai Ekologi & Adat**: Pelopor sistem akuntansi yang tidak hanya melacak arus kas komersial, tetapi juga mencatat penilaian aset biologis hutan adat dan kontribusi sosial bagi kesejahteraan komunal masyarakat adat Papua.
* **🔐 Akses Google SSO Modern**: Sistem pendaftaran dan masuk cepat sekali-klik (*one-click login*) menggunakan akun Google Gmail pengelola untuk proteksi keamanan siber yang optimal.
* **☁️ Sinkronisasi Cloud Real-Time**: Integrasi penuh dengan database cloud Supabase, menjamin seluruh data transaksi tersimpan aman dari risiko kehilangan fisik perangkat serta selalu sinkron antar-perangkat.
* **📊 Laporan Keuangan Adat Instan**: Hasilkan laporan Laba Rugi, Neraca Saldo, Arus Kas, Neraca Lajur, dan Catatan atas Laporan Keuangan (CaLK) secara dinamis dan otomatis sesuai standar akuntansi.
* **📁 Ekspor & Berbagi Multi-Format**: Kemudahan mengekspor seluruh laporan keuangan menjadi berkas Excel (.xlsx) interaktif, dokumen PDF resmi, gambar PNG, serta membagikan ringkasan laporan instan ke WhatsApp.
* **💾 Fitur Cadangan Mandiri (Backup/Restore)**: Utilitas ekspor/impor data transaksi lokal dalam format berkas `.json`, memberikan kebebasan penuh bagi pengelola untuk mengamankan data atau memindahkan pembukuan ke gadget baru secara mandiri.

---

## 🛠️ Teknologi yang Digunakan

* **Frontend**: Vanilla HTML5, TailwindCSS (via CDN), vanilla JavaScript untuk performa maksimal tanpa kompilasi build yang berat.
* **Database & Auth**: Supabase JS Client (PostgreSQL, Row Level Security, Google OAuth).
* **Native Wrapper**: Ionic Capacitor untuk konversi instan ke aplikasi Android.

---

## 🚀 Cara Menjalankan Aplikasi

Aplikasi SAKRAL dapat langsung diakses secara online tanpa perlu instalasi tambahan melalui alamat resmi berikut:

👉 **[http://sakral.gpm.feb.uncen.ac.id](http://sakral.gpm.feb.uncen.ac.id)**

Untuk menjalankannya secara offline/lokal di komputer Anda:
1. Buka file `index.html` menggunakan peramban browser Anda.
2. Untuk mensimulasikan lingkungan server lokal (dukungan PWA penuh), jalankan perintah berikut di terminal folder proyek Anda:
   ```bash
   python -m http.server 8000
   ```
   Lalu buka peramban di alamat `http://localhost:8000`.

---

©2026 SAKRAL - Sistem Informasi Akuntansi Keuangan Relasi Alam dan Adat  
Original Concept by [Kurnia Patma](https://www.instagram.com/kurniawan_patma) | Developed by [Enterdie](https://www.linkedin.com/in/papedatimur)
