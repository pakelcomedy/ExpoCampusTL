```
ExpoCampus/
│
├── index.html                   # Halaman utama (landing page)
│
├── pages/                       # Folder untuk halaman HTML individual
│   ├── about.html               # Halaman tentang kampus
│   ├── fakultas.html            # Daftar fakultas/jurusan
│   ├── fakultas-detail.html     # Detail fakultas/jurusan
│   ├── kegiatan.html            # Halaman kegiatan expo
│   ├── download.html            # Halaman untuk brosur/panduan unduhan
│   ├── leaderboard.html         # Halaman leaderboard (opsional untuk game interaktif)
│   ├── berita.html              # Halaman berita dan pengumuman
│   ├── kontak.html              # Halaman kontak dan peta kampus
│
├── assets/                      # Folder untuk aset statis (CSS, JS, gambar)
│   ├── css/                     # Folder untuk file CSS
│   │   ├── global.css           # Gaya global (layout, tipografi, dll.)
│   │   ├── fakultas.css         # Gaya untuk daftar fakultas
│   │   ├── fakultas-detail.css  # Gaya untuk detail fakultas
│   │   ├── kegiatan.css         # Gaya untuk kegiatan expo
│   │   ├── download.css         # Gaya halaman unduhan
│   │   ├── berita.css           # Gaya halaman berita
│   │   ├── kontak.css           # Gaya halaman kontak
│   │   ├── about.css            # Gaya halaman tentang kampus
│
│   ├── js/                      # Folder untuk file JavaScript
│   │   ├── global.js            # Interaksi global (misalnya, navigasi)
│   │   ├── fakultas.js          # Interaksi halaman fakultas
│   │   ├── fakultas-detail.js   # Interaksi halaman detail fakultas
│   │   ├── kegiatan.js          # Interaksi halaman kegiatan expo
│   │   ├── download.js          # Interaksi halaman unduhan
│   │   ├── berita.js            # Interaksi halaman berita
│   │   ├── kontak.js            # Interaksi halaman kontak
│   │   ├── about.js             # Interaksi halaman tentang kampus
│
│   ├── images/                  # Folder untuk file gambar (logo, ikon, dll.)
│   │   ├── logo.png             # Logo utama kampus
│   │   ├── fakultas-icon.png    # Ikon untuk fakultas/jurusan
│   │   ├── kegiatan-banner.jpg  # Gambar banner kegiatan
│   │   ├── kontak-bg.jpg        # Gambar latar belakang halaman kontak
│   │   ├── hero-banner.jpg      # Banner utama untuk landing page
│
├── firebase/                    # Folder untuk konfigurasi Firebase (jika ada)
│   ├── config.js                # Pengaturan konfigurasi Firebase
│   ├── service.js               # Logika interaksi Firebase (CRUD)
│
├── backend/                     # Folder untuk backend Node.js (opsional untuk API atau integrasi data)
│   ├── server.js                # File server utama menggunakan Express
│   ├── controllers/             # Folder untuk logika API
│   │   ├── fakultasController.js# Controller untuk logika fakultas
│   │   ├── kegiatanController.js# Controller untuk logika kegiatan
│   │   ├── beritaController.js  # Controller untuk logika berita
│   ├── routes/                  # Folder untuk definisi rute API
│   │   ├── fakultasRoutes.js    # Rute untuk fakultas
│   │   ├── kegiatanRoutes.js    # Rute untuk kegiatan
│   │   ├── beritaRoutes.js      # Rute untuk berita
│   ├── services/                # Folder untuk layanan data Firebase (opsional)
│   │   ├── firebaseService.js   # Logika CRUD Firebase
│   ├── utils/                   # Folder untuk fungsi utilitas
│   │   ├── dataUpdater.js       # Logika pembaruan data (jika ada)
│
├── .gitignore                   # File Git ignore (untuk mengecualikan file seperti node_modules)
├── package.json                 # Konfigurasi proyek dan dependensi Node.js
└── README.md                    # Dokumentasi proyek (setup, panduan penggunaan, dll.)
```
