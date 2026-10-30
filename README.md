# AktivitasKu

Personal Daily Activity and Productivity Dashboard.

## Fitur demo
- Dashboard ringkasan aktivitas dan grafik.
- Tambah, edit, hapus, cari, dan filter aktivitas.
- Kalender aktivitas.
- Statistik harian, mingguan, dan bulanan.
- Catatan pembelajaran.
- Ekspor aktivitas, catatan, dan ringkasan ke Excel (.xlsx).
- Penyimpanan demo menggunakan LocalStorage browser.

## Cara menjalankan melalui GitHub Pages
1. Unggah `index.html`, `style.css`, `script.js`, dan `README.md` ke root repository.
2. Buka **Settings → Pages**.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
5. Tunggu proses publikasi selesai dan buka URL GitHub Pages yang diberikan.

## Catatan data dan privasi
Versi ini adalah prototipe frontend. Data aktivitas disimpan di LocalStorage browser yang sedang digunakan. Data tidak tersinkronisasi otomatis antarperangkat dan tidak tersimpan di repository GitHub. Menghapus data browser dapat menghapus catatan lokal. Ekspor Excel dapat digunakan untuk membuat salinan cadangan.

Repository dan situs GitHub Pages bersifat publik. Jangan masukkan data nasabah, nomor rekening, password, kredensial, dokumen internal, atau informasi rahasia tempat magang.

## Dependensi eksternal
- Chart.js (CDN) untuk grafik.
- SheetJS (CDN) untuk ekspor Excel.
- Lucide (CDN) untuk ikon.
- Google Fonts (Inter).
