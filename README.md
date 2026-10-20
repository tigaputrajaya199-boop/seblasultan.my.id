# 🌶️ Seblak UMKM - Website Profil & Panel Admin

Website profil UMKM satu halaman (*Single-Page Application*) lengkap dengan **Panel Kelola (Admin) Dua Jendela** menggunakan HTML, CSS, dan JavaScript murni (*Vanilla*) tanpa framework atau backend. Dibuat sebagai modul proyek tugas kejuruan siswa SMK Rekayasa Perangkat Lunak (RPL).

![Preview Website Seblak UMKM](img/seblak-hero.jpg)

---

## 🌟 Fitur Utama

1. **Jendela 1 (Halaman Publik - `index.html`)**:
   - Desain modern ala website kuliner besar dengan efek *glassmorphism*, tipografi Google Fonts (*Plus Jakarta Sans* & *Inter*), serta skema warna hangat.
   - **Responsif Penuh**: Tampilan rapi mulai dari layar HP (lebar 360 px) hingga laptop tanpa scroll horizontal.
   - **Katalog 6 Produk Seblak**: Format kartu terstruktur (Foto, Nama, Porsi, Harga, Deskripsi maks 25 kata) dengan tombol pemesanan WhatsApp otomatis.
   - **Jendela Masuk Pelanggan**: Modal selamat datang interaktif untuk personalisasi nama pemesan WhatsApp layaknya aplikasi besar.
   - **Live Kitchen Order Toast**: Notifikasi pop-up simulasi pesanan dapur yang telah selesai dimasak secara berkala layaknya aplikasi restoran besar.
   - **Kontak & Lokasi**: Tabel jam operasional terstruktur, tautan WhatsApp dinamis, placeholder peta Google Maps, dan tombol mengambang (*floating WhatsApp button*).

2. **Jendela 2 (Panel Kelola / Admin - Terpadu di `index.html` & `admin.html`)**:
   - **Akses Fleksibel**: Dapat dibuka langsung di dalam Halaman Utama (`index.html`) melalui tombol floating **⚙️ Jendela 2**, tombol navigasi atas, maupun via file terpisah `admin.html`.
   - **Bebas Masalah Browser**: Karena terintegrasi langsung di halaman utama, pengaturan tersimpan di `localStorage` secara instan dan langsung ter-update di layar secara real-time tanpa kendala isolasi berkas lokal `file://` di Firefox/Chrome!
   - **Proteksi Kata Sandi**: Modal login pintu masuk dengan kata sandi: `makansantai`.
   - **Kelola Seluruh Konten**: Mengubah identitas usaha, nama pemilik, tahun berdiri, jumlah karyawan, jam buka, cerita, 3 fakta singkat, dan 3 keunggulan.
   - **Kelola 6 Produk Seblak**: Mengubah foto produk, nama, harga, porsi, dan deskripsi produk secara fleksibel.
   - **Pengaturan Warna Tema**: Pengubah warna dinamis (`--warna-utama`, `--warna-aksen`, `--warna-latar`, `--warna-harga`) dengan *Color Picker*.
   - **Reset ke Data Awal**: Fitur mengembalikan seluruh pengaturan ke setelan default awal jika terjadi kesalahan.

---

## 📁 Struktur Berkas

```text
seblak-umkm/
│
├── index.html        # Jendela 1: Halaman publik utama
├── admin.html        # Jendela 2: Panel kelola admin (Password: makansantai)
├── style.css         # Lembar gaya terpadu (CSS Variables, Flexbox, Grid, Media Queries)
├── script.js         # Logika JavaScript murni, LocalStorage & Notifikasi Live
├── README.md         # Dokumentasi proyek untuk GitHub
├── .gitignore        # Berkas pengecualian Git
└── img/              # Folder aset foto
    ├── seblak-hero.jpg
    ├── seblak-1.jpg
    ├── seblak-2.jpg
    ├── seblak-3.jpg
    ├── seblak-4.jpg
    ├── seblak-5.jpg
    └── seblak-6.jpg
```

---

## 🚀 Cara Menjalankan di Komputer / Laptop

1. Unduh atau clone repositori ini:
   ```bash
   git clone https://github.com/USERNAME/seblak-umkm.git
   cd seblak-umkm
   ```
2. Buka berkas `index.html` dengan klik dua kali di penjelajah berkas (*file manager*) atau buka menggunakan browser kesayangan Anda (Google Chrome, Firefox, Edge).
3. Untuk membuka panel admin, buka `admin.html` atau klik tombol **⚙️ Kelola Toko** di bilah navigasi (header) atas.
4. Masukkan kata sandi: `makansantai`.

---

## 🌐 Cara Publikasi ke GitHub Pages (Gratis)

Agar website ini dapat diakses oleh siapa saja lewat internet:
1. Buka repositori proyek ini di situs **GitHub**.
2. Masuk ke menu **Settings** > **Pages** (di bilah navigasi sebelah kiri).
3. Pada bagian **Build and deployment** > **Branch**, pilih cabang `main` dan folder `/ (root)`.
4. Klik **Save**.
5. Tunggu 1–2 menit, website Anda akan aktif di alamat:
   `https://USERNAME.github.io/seblak-umkm/`

---

## 👨‍💻 Kontributor

- **Pengembang**: Siswa SMK PGRI Singosari (Jurusan Rekayasa Perangkat Lunak)
- **Teknologi**: HTML5 Semantik, CSS3 Murni, Vanilla JavaScript (DOM & LocalStorage API)
- **Lisensi**: MIT License (Bebas digunakan dan dikembangkan untuk keperluan edukasi)
