# Website Portofolio — Syubban Fikri Salim

Website statis HTML, CSS, dan JavaScript. Siap dipublikasikan menggunakan GitHub Pages.

## Isi folder
- `index.html` — konten utama website
- `style.css` — desain responsif modern navy
- `script.js` — menu navigasi mobile dan tahun otomatis
- `assets/` — tempat menyimpan foto dan CV PDF

## Cara publikasi melalui GitHub
1. Login ke https://github.com
2. Tekan **New repository**.
3. Isi nama repository: `portofolio-syubban-fikri-salim`.
4. Pilih **Public**, lalu tekan **Create repository**.
5. Unggah `index.html`, `style.css`, `script.js`, `README.md`, dan folder `assets`.
6. Buka **Settings → Pages**.
7. Pada **Build and deployment**, pilih **Deploy from a branch**.
8. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
9. Tunggu proses publikasi. Alamat website akan berbentuk:
   `https://USERNAME.github.io/portofolio-syubban-fikri-salim/`

## Menambahkan foto
1. Siapkan foto profesional berbentuk JPG atau PNG.
2. Unggah foto ke folder `assets` dengan nama `foto-syubban.jpg`.
3. Di `index.html`, cari bagian `div class="portrait-placeholder"` dan ganti elemen tersebut dengan:
   `<img class="profile-photo" src="assets/foto-syubban.jpg" alt="Foto Syubban Fikri Salim">`
4. Tambahkan aturan CSS berikut di bagian akhir `style.css`:
   `.profile-photo{width:100%;height:100%;object-fit:cover;object-position:center;display:block}`

## Menambahkan CV PDF
1. Simpan CV final dalam format PDF.
2. Beri nama file `CV-Syubban-Fikri-Salim.pdf`.
3. Unggah ke folder `assets`.
4. Tautan CV di website sudah diarahkan ke `assets/CV-Syubban-Fikri-Salim.pdf`.

## Catatan akurasi
- Konten pengalaman magang dan organisasi diringkas dari informasi CV yang tersedia.
- Tidak ada angka pencapaian kerja, jumlah kandidat, atau proyek rekrutmen fiktif.
- Bagian foto dan CV PDF perlu diisi dengan file milik pengguna sebelum dibagikan.
- Nomor WhatsApp, email, dan LinkedIn memakai informasi kontak yang diberikan pengguna.
