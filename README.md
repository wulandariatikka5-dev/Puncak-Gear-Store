# Puncak Gear — Website Jual Perlengkapan Mendaki

Website statis (HTML, CSS, JS) dengan landing page bertema pegunungan. Pengunjung bisa melihat, memfilter, dan memesan produk lewat WhatsApp. Pemilik bisa menambah produk (gambar, deskripsi, harga) lewat formulir.

## Struktur
- `index.html` — halaman utama
- `style.css` — tampilan
- `script.js` — daftar produk, formulir, filter, dan tombol pesan

## Menjalankan di komputer
Buka `index.html` di browser. Tidak perlu instalasi.

## Mengunggah ke GitHub Pages
1. Buat repository baru di GitHub, lalu unggah keempat file ini.
2. Buka **Settings → Pages**.
3. Pada **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit. Situs tampil di `https://USERNAME.github.io/NAMA-REPO/`.

## Pengaturan
- **Nomor WhatsApp:** ubah `WA_NUMBER` di bagian atas `script.js` (format `62812...`).
- **Kategori:** ubah daftar `CATS` di `script.js`.
- **Produk bawaan permanen:** edit array `DEFAULTS` di `script.js`. Isi `img` dengan path gambar di repo (mis. `images/tenda.jpg`) atau URL gambar.

## Catatan penting
Produk yang ditambah lewat formulir tersimpan di **localStorage browser** pemilik, jadi tidak terlihat oleh pengunjung lain. Agar produk tampil untuk semua orang, tambahkan ke `DEFAULTS` lalu commit ke GitHub. Untuk admin dengan database sungguhan, Anda perlu backend (mis. Firebase atau Supabase).
