# Bonsai Garden 15 — Website Prototype

## Isi paket
- `index.html`: website katalog responsif, dengan admin dashboard prototipe.
- `assets/bonsai-landscape-asli.png`: foto bonsai yang disediakan di percakapan (jika tersedia pada saat paket dibuat).

## Cara mencoba
1. Ekstrak ZIP.
2. Buka `index.html` dengan browser modern.
3. Klik `Admin dashboard` di bagian paling bawah untuk menambah, mengedit, atau menghapus produk.
4. Data admin prototipe disimpan di localStorage browser yang sedang dipakai.

## Konfigurasi WhatsApp
Di dalam `index.html`, cari:
`const WA_NUMBER = "6281546449236";`
Isi dengan nomor WhatsApp bisnis format internasional tanpa tanda +, misalnya awalan 62. Nomor WhatsApp bisnis sudah dikonfigurasi.

## Sebelum dipublikasikan
Ini masih prototipe front-end, bukan sistem produksi. Dashboard belum punya autentikasi server dan data produk hanya tersimpan di browser lokal. Untuk live website multi-perangkat, sambungkan ke backend/database dan login admin yang aman. Isi harga, jenis pohon, tinggi, dan stok hanya setelah dikonfirmasi.
