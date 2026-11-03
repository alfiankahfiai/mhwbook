# Flipbook HTML5 - Sistem Manajemen PT. Mahawangsa

Paket flipbook interaktif dari PDF sumber, terdiri dari 108 halaman.

## Fitur
- Tampilan dua halaman (spread) untuk halaman isi pada layar lebar.
- Sampul pertama dan halaman terakhir tampil satu halaman (`showCover: true` dan density `hard`).
- Animasi membalik halaman, navigasi tombol, keyboard, input nomor halaman, dan mode layar penuh.
- Layout responsif untuk desktop dan perangkat seluler.
- Gambar halaman telah dioptimalkan dalam format WebP.

## Menjalankan lokal
Cara paling mudah: buka `index.html` melalui browser saat perangkat terhubung ke internet. Flipbook memakai pustaka PageFlip dari CDN.
Jika browser membatasi file lokal, jalankan server lokal dari folder ini, misalnya:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Hosting di GitHub Pages
1. Ekstrak ZIP ini.
2. Unggah `index.html` dan folder `assets/` ke root repository GitHub.
3. Buka **Settings > Pages**.
4. Pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu simpan.
5. Buka URL Pages yang diberikan GitHub.

Catatan: koneksi internet dibutuhkan untuk memuat pustaka PageFlip dari CDN. Jangan mengubah nama folder `assets/pages` tanpa menyesuaikan path pada `index.html`.
