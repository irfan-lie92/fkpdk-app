Gunakan IDE Favorit Anda

Jika Anda ingin bekerja secara lokal menggunakan IDE sendiri, Anda dapat clone repositori ini dan mendorong (push) perubahan Anda. Perubahan yang telah dipush juga akan terlihat di Lovable.

Syarat utama adalah Anda harus memiliki Node.js & npm yang sudah terinstal – instalasi menggunakan nvm

Ikuti langkah-langkah berikut:

# Langkah 1: Clone repositori menggunakan URL Git proyek.
git clone https://github.com/irfan-lie92/desa-forum-komunikasi-plus.git

# Langkah 2: Masuk ke direktori proyek.
cd desa-forum-komunikasi-plus

# Langkah 3: Instal semua dependensi yang dibutuhkan.
npm i

# Langkah 4: Jalankan server pengembangan dengan fitur auto-reload dan pratinjau instan.
npm run dev

Edit File Langsung di GitHub

    Arahkan ke file yang ingin Anda ubah.

    Klik tombol "Edit" (ikon pensil) di kanan atas tampilan file.

    Lakukan perubahan dan commit perubahan tersebut.

Gunakan GitHub Codespaces

    Arahkan ke halaman utama repositori Anda.

    Klik tombol "Code" (tombol hijau) di kanan atas.

    Pilih tab "Codespaces".

    Klik "New codespace" untuk menjalankan lingkungan Codespace baru.

    Edit file langsung di dalam Codespace, lalu commit dan push perubahan Anda setelah selesai.

Teknologi yang Digunakan dalam Proyek Ini

Proyek ini dibangun menggunakan:

    Vite

    TypeScript

    Next.js

    shadcn-ui

    Tailwind CSS
  
Database (PostgreSQL):

    Schema lengkap dengan 8 tabel utama
    Data seed untuk testing
    Indexing untuk performa optimal
    Trigger untuk auto-update timestamps
    Activity logging untuk audit trail

API Backend (Node.js/Express):

    Controllers untuk setiap modul (dashboard, libraries, users, documents, reports)
    Routes dengan RESTful endpoints
    CRUD operations lengkap
    Pagination dan filtering
    Error handling yang proper

Fitur CRUD yang dapat diedit di dashboard admin:

    Total Perpustakaan - Kelola data perpustakaan
    Pengguna Aktif - Kelola data pengguna
    Diskusi Aktif - Data otomatis dari tabel discussions
    Kegiatan Bulan Ini - Data otomatis dari tabel events
    Kelola Pengguna - CRUD pengguna lengkap
    Kelola Dokumen - CRUD dokumen lengkap
    Laporan - CRUD laporan lengkap

