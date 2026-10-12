# RuangStok — Sistem Persediaan dan Analisis HPP pada Toko Merchandise

Aplikasi web untuk mengelola persediaan dan menganalisis Harga Pokok Penjualan (HPP) pada toko merchandise. Mendukung pencatatan produk, supplier, barang masuk, barang keluar, kartu persediaan, hingga laporan laba dan margin dengan metode **moving average**.

Demo web: [Buka RuangStok](https://kaeygogirl.github.io/Sistem-Persediaan-dan-Analisis-HPP-pada-Toko-Merchandise-/)

Demo di-host secara publik melalui GitHub Pages.

## Fitur

- **Dashboard** — ringkasan performa toko: perhatian persediaan, komposisi nilai persediaan per kategori, pembelian terbaru, penjualan terbaru, dan kontribusi laba produk.
- **Daftar Produk** — kelola katalog, harga jual, stok, serta aktif/nonaktifkan produk tanpa menghapus riwayat.
- **Supplier** — kelola mitra pemasok dan riwayat pembelian.
- **Barang Masuk** — catat pembelian dan biaya perolehan dengan metode **moving average**.
- **Barang Keluar** — catat penjualan, retur, dan pergerakan persediaan dalam satu alur.
- **Kartu Persediaan** — telusuri jejak pergerakan dan saldo tiap produk.
- **Analisis HPP & Laba** — evaluasi margin, harga jual, kerugian persediaan, dan laporan periodik.
- **Settings** — atur identitas toko, kebijakan persediaan, tampilan, serta master data (kategori & ukuran).

## Detail Modul Analisis

- **Nilai persediaan per kategori** — snapshot stok × HPP rata-rata.
- **Kontribusi laba per produk** — memakai HPP snapshot setiap transaksi.
- **Evaluasi harga jual** — margin indikatif berdasarkan harga jual default.
- **Kerugian persediaan** — dicatat terpisah dari laba kotor penjualan.
- **Laporan periodik** — perbandingan nilai transaksi bersih per periode.

## Settings

- **Pengaturan umum** — identitas teks untuk nota dan aplikasi.
- **Penukaran & persediaan** — penukaran barang customer maksimal 2 hari setelah pembelian.
- **Tampilan & personalisasi** — preferensi visual tersimpan di browser.
- **Kelola kategori & ukuran** — kategori bertingkat dan ukuran per sub-kategori.

## Teknologi

- HTML, CSS, JavaScript
- Visual Studio Code, Supabase
- GitHub Pages (hosting)


