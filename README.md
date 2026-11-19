# Merly Food & Beverage

Dashboard pembukuan usaha F&B, mobile first. Transaksi dicatat lewat chat ("jual 40 porsi 1,2jt", "belanja ayam 350rb"), lalu otomatis dipisah jadi pemasukan atau pengeluaran dan dimasukkan ke kategorinya.

## Fitur
- **Catat**: input transaksi lewat chat, bisa juga tanya "untung bulan ini berapa?"
- **Analisa**: pemasukan, pengeluaran, keuntungan per hari / minggu / bulan / tahun / rentang tanggal, dibandingkan dengan periode sebelumnya. Ada gauge laba usaha (Rugi / Impas / Sehat), evaluasi, grafik, dan donut kategori.
- **Transaksi**: daftar semua catatan dengan pencarian, filter waktu, dan edit.

Batas margin mengikuti patokan umum: di bawah 10% impas/menipis, 20% ke atas sehat. Investasi dan prive dipisah dari laba usaha.

## Menjalankan
Satu file statis: buka `index.html` di browser, atau aktifkan GitHub Pages dari branch `main`.

Di luar Claude, app berjalan dalam mode lokal: data disimpan di browser (localStorage) dan pembacaan chat memakai parser bawaan, bukan AI.

Font: Geist. Warna: Tailwind stone + brand maroon `#390303`.
