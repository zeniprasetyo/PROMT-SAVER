# 📌 Simpanan Saya

Aplikasi web sederhana untuk menyimpan **prompt** dan **link** (Threads, Instagram, TikTok, YouTube, X, website, dll.) supaya tidak lupa.

Satu file saja (`index.html`), tanpa install, tanpa library tambahan.

## Fitur

- Simpan **prompt** atau **link** dengan judul, sumber, dan tag
- Sumber link terdeteksi otomatis (Threads, Instagram, TikTok, YouTube, X, GitHub, dll.)
- Cari berdasarkan judul, isi, sumber, atau tag
- Filter: Semua / Prompt / Link / ⭐ Favorit
- Tombol **Salin** untuk prompt dan **Buka** untuk link
- Edit dan hapus item
- **Backup** ke file JSON dan **Pulihkan** dari file JSON
- Tampilan otomatis menyesuaikan mode terang/gelap, nyaman di HP

## Cara Pakai

1. Unduh atau clone repo ini.
2. Pastikan file utamanya bernama `index.html`.
3. Buka `index.html` di browser, atau pasang lewat GitHub Pages (lihat di bawah).

## Pasang di GitHub Pages

1. Buka **Settings → Pages** di repo ini.
2. Pada **Source** pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit. Alamatnya:
   `https://USERNAME.github.io/NAMA-REPO/`

## Penyimpanan Data

Di GitHub Pages, data disimpan di **browser masing-masing perangkat** (localStorage).

- Data **tidak sinkron** antara HP dan laptop.
- Membersihkan data browser dapat **menghapus** simpananmu.
- Gunakan tombol **Backup (JSON)** secara berkala dan simpan filenya di tempat aman, misalnya Google Drive.
- Jangan simpan password atau data rahasia di aplikasi ini.

> Catatan: versi yang dijalankan di Claude.ai (artifact) memakai database bawaan sehingga data sinkron di semua perangkat. Versi di repo ini otomatis berjalan dalam mode lokal.

## Teknologi

HTML, CSS, dan JavaScript murni dalam satu file.

## Lisensi

Bebas dipakai dan dimodifikasi untuk keperluan pribadi.
