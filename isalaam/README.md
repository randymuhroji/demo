# iSalaam — situs statis (demo)

Isi folder:

- `index.html` — landing page
- `login.html` — halaman masuk ke Console (mode demo: email apa saja + kata sandi minimal 6 karakter)
- `console.html` — Console pengurus masjid (dasbor, profil, donasi, keuangan, kegiatan, inventaris, panel kementerian)
- `app.html` — aplikasi jamaah (link khusus untuk dibagikan ke jamaah)

## Deploy

Semua file mandiri (tanpa build, tanpa server). Unggah seluruh isi folder ke hosting statis mana pun:
Netlify, Vercel, GitHub Pages, Cloudflare Pages, Firebase Hosting, atau folder `public_html` di cPanel.

Link khusus jamaah: `https://domain-anda/app.html`

## Catatan

- Login hanya gerbang demo (disimpan di browser), bukan autentikasi sungguhan. Untuk produksi, ganti dengan backend/auth.
- Semua angka, nama masjid, dan jadwal salat adalah data contoh.
- Font dimuat dari Google Fonts; tanpa internet, halaman tetap jalan dengan font sistem.
