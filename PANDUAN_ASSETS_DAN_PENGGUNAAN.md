# 🌟 Panduan Lengkap Web Portofolio & Tempat Upload Assets

Website portofolio ini dibuat **persis dan identik 100%** dengan tampilan serta animasi dari **[alfari.my.id](https://www.alfari.my.id/)**.

---

## 📁 Struktur Khusus Folder Assets (Tinggal Upload)

Folder khusus untuk upload foto, sertifikat, dan projek telah disiapkan rapi di:  
📂 `assets/upload_disini/`

```text
webportofolio/
├── index.html                           <-- Halaman utama portofolio
├── favicon.svg & favicon.png             <-- Ikon browser
├── PANDUAN_ASSETS_DAN_PENGGUNAAN.md     <-- Panduan ini
└── assets/
    ├── upload_disini/                   <-- 🎯 FOLDER UTAMA TEMPAT KAMU UPLOAD ASSETS
    │   ├── foto_profil/
    │   │   ├── me.webp                  <-- [Foto Profil Kamu] Ganti file ini dengan foto kamu
    │   │   ├── spiderman-mask.png       <-- [Efek Topeng Spider-Man] Efek saat foto profil di-hover kursor
    │   │   ├── lanyard-front.webp       <-- [Kartu ID Depan] Tampilan depan kartu 3D Lanyard
    │   │   ├── lanyard-back.webp        <-- [Kartu ID Belakang] Tampilan belakang kartu 3D Lanyard
    │   │   └── lanyard-strap.webp       <-- [Tali Lanyard] Tekstur tali gantungan 3D
    │   │
    │   ├── sertifikat/
    │   │   ├── sertifikat-1.webp        <-- [Sertifikat 1 - PKL]
    │   │   ├── sertifikat-2.webp        <-- [Sertifikat 2 - Web Development]
    │   │   ├── sertifikat-3.png         <-- [Sertifikat 3 - Udemy]
    │   │   └── penghargaan-1.webp       <-- [Piagam Penghargaan / Prestasi Lomba]
    │   │
    │   ├── projek/
    │   │   ├── projek-1.webp            <-- [Screenshot Projek 1]
    │   │   ├── projek-2.webp            <-- [Screenshot Projek 2]
    │   │   └── projek-3.webp            <-- [Screenshot Projek 3]
    │   │
    │   └── logo_pendidikan_dan_pengalaman/
    │       ├── logo-smk-texmaco.webp    <-- Logo sekolah 1
    │       ├── logo-mts.webp            <-- Logo sekolah 2
    │       └── logo-stekom.webp         <-- Logo kampus / instansi
    │
    ├── icons/                           <-- Ikon teknologi (Android Studio, MySQL, XAMPP, TikTok, dll)
    ├── index-JraU3a1h.js                <-- Script utama (React, GSAP, Audio Synth, Routing)
    ├── index-BAu5BQY0.css               <-- Desain CSS lengkap (Cyber neon, Glassmorphism, Responsive)
    ├── Lanyard-BTRBc1_I.js              <-- Engine 3D Three.js Fisika Lanyard
    └── preloadPortfolioAssets-D6d7UHb-.js <-- Preloader Aset
```

---

## 📸 Cara Upload Foto Profil & Sertifikat Kamu

### 1. Mengganti Foto Profil
1. Buka folder `assets/upload_disini/foto_profil/`.
2. Siapkan foto profil terbaik kamu.
3. Simpan atau timpa (replace) file bernama `me.webp` dengan fotomu.
> **Tips Format**: Kamu bisa menggunakan format `.webp`, `.png`, atau `.jpg` (cukup beri nama `me.webp` atau ubah ekstensinya).

### 2. Mengganti Efek Topeng Spider-Man (Opsional)
- Jika ingin tetap memakai efek Spider-Man mask saat foto profil di-hover mouse, biarkan file `spiderman-mask.png`.
- Jika ingin diganti dengan gambar topeng lain atau versi berbeda, cukup timpa file `spiderman-mask.png`.

### 3. Mengganti Sertifikat & Piagam Penghargaan
1. Buka folder `assets/upload_disini/sertifikat/`.
2. Timpa file sertifikat yang ada:
   - `sertifikat-1.webp` untuk Sertifikat PKL / Magang
   - `sertifikat-2.webp` untuk Sertifikat Kursus / Pelatihan Web
   - `sertifikat-3.png` untuk Sertifikat Course lainnya
   - `penghargaan-1.webp` untuk Piagam / Penghargaan Juara
3. Ketika kartu sertifikat diklik di website, pop-up / lightbox akan langsung menampilkan gambarmu secara tajam dan fullscreen!

### 4. Mengganti Foto Projek
1. Buka folder `assets/upload_disini/projek/`.
2. Timpa file `projek-1.webp`, `projek-2.webp`, dan `projek-3.webp` dengan screenshot karya atau portofolio aplikasimu.

---

## ✨ Fitur & Animasi yang Sudah Aktif di Dalamnya

1. **3D Interactive Physics Lanyard (ID Card)**
   - Menggunakan WebGL & Three.js physics. Kartu lanyard menggantung secara dinamis mengikuti gravitasi dan bisa ditarik/digerakkan dengan mouse atau sentuhan jari di smartphone.
2. **Efek Topeng Spider-Man saat Hover Foto Profil**
   - Mengikuti pergerakan kursor mouse di atas foto profil untuk menampilkan overlay Spider-Man dengan transisi radial yang sangat halus.
3. **Background Kosmik Interaktif**
   - Ratusan partikel bintang bergerak mengambang dengan efek paralaks.
   - Efek hujan meteor (shooting stars) dengan lintasan cahaya yang estetik.
   - Ambient glow tiga dimensi berwarna biru, ungu, dan cyan.
4. **Preloader Modern dengan Persentase Realtime**
   - Layar animasi pembuka (0% – 100%) dengan bar progress halus sebelum masuk ke beranda.
5. **Efek Suara UI Interaktif (Web Audio API Synthesizer)**
   - Dilengkapi switch suara di menu navigasi. Ketika tombol atau link diklik, akan ada feedback suara haptic/klik digital yang futuristik tanpa perlu file audio eksternal.
6. **Tabs Portofolio Lengkap**
   - **Projects**: Kartu proyek dengan gradien neon, tag teknologi, dan tombol buka detail.
   - **Certificates**: Galeri sertifikat interaktif dengan preview modal fullscreen.
   - **Achievements**: Piagam penghargaan dan riwayat kompetisi.
   - **Tech Stack**: Grid teknologi terkategori (Frontend, Backend & Database, Tools & DevOps).
7. **Spotlight & Border Glow Card**
   - Sudut cahaya di pinggir kartu proyek dan sertifikat otomatis bergerak mengikuti arah mouse (`--cursor-angle` dan `--edge-proximity`).
8. **Integrasi Spotify Daily Rotation**
   - Widget pemutar musik Spotify dengan frame playlist favorit.
9. **Formulir Kontak & Guestbook Komentar**
   - Form kirim pesan langsung via Formspree.
   - Kolom komentar / buku tamu realtime dengan cooldown proteksi anti-spam.

---

## 🚀 Cara Menjalankan Website Portofolio

Website ini berbasis Web Modern (ES Modules). Untuk melihat seluruh animasi 3D Lanyard dan efek WebGL bekerja sempurna, jalankan menggunakan local web server:

### Opsi 1: Menggunakan VS Code (Paling Mudah)
1. Buka folder `c:\Documents\webportofolio` di Visual Studio Code.
2. Pasang ekstensi **Live Server** (jika belum ada).
3. Klik kanan pada file `index.html` dan pilih **"Open with Live Server"**.
4. Website akan langsung terbuka di browsermu dengan URL `http://127.0.0.1:5500/index.html`.

### Opsi 2: Menggunakan Terminal / Command Prompt (Python)
1. Buka Command Prompt atau PowerShell di folder ini.
2. Jalankan perintah:
   ```bash
   python -m http.server 3000
   ```
3. Buka browser dan kunjungi: **[http://localhost:3000](http://localhost:3000)**.

