# Katalog Editable — siap Vercel

Katalog kosong dengan tampilan mobile-friendly dan admin sederhana.

## Jalankan
1. Install Node.js.
2. Jalankan `npm install`
3. Jalankan `npm run dev`

## Deploy Vercel
Upload folder ini ke GitHub lalu import repository di Vercel. Framework akan terdeteksi sebagai Vite.

## Admin
Klik ikon kunci di kanan atas.
Password awal: `admin123`

**Penting:** password ini hanya cocok untuk demo/prototipe karena data disimpan di browser (localStorage). Untuk katalog produksi dengan banyak admin/perangkat, gunakan database + autentikasi server.

## Data
Produk, harga, kategori, isi CTN, status, dan foto yang diupload tersimpan di localStorage browser. Foto disimpan sebagai data URL. Untuk ratusan produk sebaiknya versi berikutnya memakai database/storage.
