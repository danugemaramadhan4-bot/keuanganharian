KEUANGAN HARIAN - PWA

Isi folder ini:
- index.html       aplikasi utama
- manifest.json    identitas aplikasi/install
- sw.js            mode offline/cache
- icons/           ikon aplikasi
- backup-keuangan.json  backup data pengguna

Catatan:
PWA perlu dijalankan dari HTTPS atau localhost agar service worker dan instalasi aplikasi bekerja.
Membuka index.html langsung lewat file:// hanya untuk melihat aplikasi, bukan mode install PWA.

Fitur yang sudah ada di project:
- Pemasukan
- Pengeluaran
- Pelunasan
- Portofolio
- Transaksi
- Backup/restore JSON
- Pengaturan gaji, batas, tabungan, kewajiban
- Grafik 7 hari berbasis tanggal
- Penyimpanan localStorage/offline
