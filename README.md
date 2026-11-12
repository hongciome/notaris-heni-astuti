# Sigit Prakoso — Portfolio Website

Website portofolio minimalis bergaya Apple, dibuat dengan HTML, CSS, dan JavaScript murni. Tidak membutuhkan Node.js atau framework.

## Menjalankan di Ubuntu

1. Ekstrak folder `sigit-portfolio`.
2. Buka folder tersebut di VS Code: **File → Open Folder**.
3. Cara paling mudah: pasang ekstensi **Live Server** di VS Code, lalu klik kanan `index.html` → **Open with Live Server**.
4. Alternatif tanpa ekstensi, buka Terminal di folder project lalu jalankan:

   ```bash
   python3 -m http.server 8000
   ```

   Buka `http://localhost:8000` di browser.

## Bagian yang perlu kamu personalisasi

- `index.html`: ubah deskripsi profil, keahlian, proyek, tautan GitHub, dan email.
- Ganti `emailkamu@example.com` dengan email aktif pada tautan `mailto:`.
- Tautan GitHub contoh saat ini mengarah ke `https://github.com/`; ganti dengan URL repository masing-masing.
- Kartu proyek saat ini adalah contoh tampilan, bukan klaim proyek yang sudah selesai. Ganti dengan karya asli dan screenshot milikmu.
- `style.css`: atur warna, ukuran, jarak, dan layout.
- `script.js`: mengatur menu navigasi mobile dan tahun otomatis.

## Struktur folder

```text
sigit-portfolio/
├── index.html
├── style.css
├── script.js
└── README.md
```

Font DM Sans dan Manrope dimuat dari Google Fonts. Jika sedang offline, website tetap berjalan dengan font sistem sebagai fallback.
