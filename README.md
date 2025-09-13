# DanaKita - Versi LocalStorage (Tanpa Firebase)

Aplikasi manajemen keuangan **tanpa backend**. Semua data (transaksi, anggaran, tujuan) disimpan di **LocalStorage** browser.

## Fitur
- Tambah/edit/hapus **Transaksi**, **Anggaran**, **Tujuan**
- **Grafik arus kas** 6 bulan terakhir (Chart.js)
- **Ekspor/Impor** data ke/dari file JSON
- Desain statis (Tailwind CDN) → cocok untuk Netlify/Static Hosting

## Cara Pakai
1. Unggah folder ini ke Netlify (drag-and-drop) **atau** buka `index.html` langsung di browser.
2. Data otomatis tersimpan di LocalStorage (`danakita_local_v1`).
3. Gunakan tombol **Ekspor/Impor** di sidebar untuk backup/restore.

> Catatan: Data LocalStorage bersifat per-browser & per-domain.
