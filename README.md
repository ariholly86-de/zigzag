# Issho Cafe Commercial Edition

Versi komersial terpisah dari Issho Cafe untuk pengembangan, demo, penjualan, dan penyewaan.

## Prinsip isolasi
- Repository produksi asli `ariholly86-de/issho-cafe-online-v3` tidak diubah oleh aplikasi ini.
- Data tenant komersial harus memakai Supabase/schema/credentials terpisah dari produksi asli.
- Setiap tenant memiliki nama cafe, konfigurasi, pengguna, produk, order, pembayaran, stok, dan pengaturan sendiri.

## Admin Center
Admin Center akan menjadi pusat pengelolaan seluruh tenant: membuat cafe baru, mengaktifkan/nonaktifkan tenant, mengatur masa sewa, branding, dan konfigurasi.

## Fitur basis
Customer menu, QR meja, order, kasir, dapur, stok, pembayaran/QRIS, notifikasi, dan pengaturan cafe akan menggunakan basis menu Issho Cafe yang dicopy untuk edisi komersial.
