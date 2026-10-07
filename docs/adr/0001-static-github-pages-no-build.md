# Deploy sebagai static site di GitHub Pages, branch main root, tanpa build step

Portal hanya berisi HTML/CSS/JS statis (judul, subjudul, tujuh Tautan Keluar, footer) — tidak ada logika server atau data dinamis. Kami deploy langsung dari branch `main` (root folder) ke GitHub Pages di akun `diperma`, tanpa GitHub Actions atau proses build apa pun. Alternatif seperti Vercel/Netlify atau workflow Actions ditolak karena menambah dependency dan langkah deploy yang tidak dibutuhkan untuk situs sesederhana ini.
