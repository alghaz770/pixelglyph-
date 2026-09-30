# PixelGlyph

Website satu halaman yang mengubah gambar menjadi susunan simbol, angka, atau huruf yang tetap membentuk gambar aslinya — mirip ASCII art, tapi dengan kontrol tampilan dan pilihan set karakter.

## Cara pakai
1. Buka `index.html` langsung di browser (double-click, atau klik kanan → Open with → browser apa pun). Tidak perlu server atau instalasi.
2. Di bagian "Ubah gambarmu", jatuhkan (drag & drop) sebuah gambar atau klik kotak putus-putus untuk memilih file dari perangkatmu.
3. Atur:
   - **Set karakter** — Klasik, Rinci, Blok, Biner, atau tulis sendiri urutan karakter dari terang ke gelap.
   - **Kepadatan** — jumlah kolom karakter (semakin besar, semakin detail tapi semakin panjang).
   - **Mode warna** — tinta monokrom (satu warna) atau warna asli gambar per karakter.
   - **Balik terang/gelap** — untuk membalik pemetaan kecerahan.
4. Hasilnya langsung tampil di panel kanan. Unduh sebagai `.png` (gambar, kualitas penuh), `.jpg` (gambar, ukuran file lebih kecil — cocok untuk memori terbatas), atau `.txt` (teks mentah), atau salin teksnya langsung.

## Catatan teknis
- Satu file HTML mandiri (`index.html`), berisi CSS dan JavaScript — tidak ada dependensi build.
- Seluruh proses konversi gambar terjadi di browser pengguna (client-side), memakai Canvas API. Tidak ada gambar yang diunggah ke server mana pun.
- Font yang dipakai (Fraunces & IBM Plex Mono) diambil dari Google Fonts lewat CDN; jika perangkat sedang offline, halaman tetap berjalan dengan font cadangan sistem.
- Desain responsif: tata letak menyesuaikan dari layar desktop hingga ponsel.

## Menghosting online
File ini bisa langsung diunggah ke layanan hosting statis apa pun (GitHub Pages, Netlify, Vercel, cPanel, dll) tanpa perubahan apa pun — cukup unggah `index.html`.
