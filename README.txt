MY MUSIC — STARTER PROJECT (GRATIS)

Isi folder:
- index.html: aplikasi pemutar musik
- manifest.json: metadata PWA
- service-worker.js: cache dasar agar antarmuka bisa dibuka kembali saat offline
- icon-192.png dan icon-512.png: ikon aplikasi

CARA MENJALANKAN:
1. Upload semua file dan folder ini ke sebuah hosting HTTPS.
2. Buka URL hosting di Chrome Android.
3. Untuk pemasangan sebagai PWA, buka menu Chrome (⋮) dan cari "Tambahkan ke layar utama" atau "Install app" bila tersedia.
4. Untuk membuat paket Android, buka https://www.pwabuilder.com/ dan masukkan URL PWA yang sudah online. Ikuti petunjuk packaging Android yang tersedia.

CATATAN:
- Pemutar ini memutar file audio yang dipilih pengguna dari perangkat; lagu tidak diunggah.
- Versi awal tidak menyimpan file musik di dalam aplikasi, tidak menyediakan katalog streaming, dan belum menjamin pemutaran di latar belakang setelah aplikasi ditutup.
- PWABuilder membutuhkan PWA yang sudah online melalui HTTPS. Paket Android/TWA dapat memiliki langkah konfigurasi lanjutan; membuat dan memasang APK uji tidak sama dengan menerbitkan aplikasi di Play Store.
- Simpan kode sumber dan detail signing key dengan aman jika membuat paket bertanda tangan.
