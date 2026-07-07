# 🌸 Nazwa Skincare — Business Overview

## 1. Nama Bisnis, Deskripsi, dan Value Proposition

**Nama Bisnis:** Nazwa Skincare

**Deskripsi:**
Nazwa Skincare adalah toko skincare online dengan tampilan katalog digital (single-page web app) yang menjual produk perawatan wajah, tubuh, dan bibir dengan tema visual *pink/rose* yang lembut dan feminin. Pelanggan dapat menelusuri katalog, menambahkan produk ke keranjang, memilih metode pembayaran, lalu pesanan otomatis diteruskan ke WhatsApp pemilik toko dalam format bukti pemesanan yang rapi.

**Value Proposition:**
- Belanja skincare mudah dan cepat tanpa perlu install aplikasi — cukup buka halaman web.
- Konfirmasi pesanan otomatis terkirim ke WhatsApp toko lengkap dengan nomor invoice, rincian belanja, dan metode pembayaran.
- Pilihan pembayaran fleksibel: COD, QRIS, transfer bank (SeaBank), dan e-wallet (DANA).
- ![NAX Preview](images/metode pembayaran.jpeg)
- Pengalaman berbelanja yang menarik secara visual (animasi halus, pencarian produk real-time, filter kategori).

## 2. Target Market & Segmentasi Pelanggan

- **Demografi utama:** Perempuan usia 15–35 tahun, pelajar/mahasiswa dan pekerja muda.
- **Segmentasi psikografis:** Konsumen yang peduli perawatan kulit harian dengan budget menengah ke bawah (harga produk berkisar Rp 15.000–Rp 65.000).
- **Segmentasi perilaku:**
  - Pembeli impulsif via media sosial (Instagram) — terlihat dari kolom Instagram pada form checkout.
  - Pembeli berulang (repeat order) untuk kebutuhan rutin seperti facial wash dan moisturizer.
- **Wilayah:** Berbasis lokal/domestik Indonesia (harga dalam Rupiah, pembayaran via bank & e-wallet lokal).

## 3. Analisis Pasar Singkat & Kompetitor

**Kondisi pasar:**
Industri skincare lokal Indonesia tumbuh pesat, didorong tren *self-care* dan kemudahan belanja online melalui media sosial dan WhatsApp Business. Konsumen muda cenderung memilih brand lokal dengan harga terjangkau dan interaksi personal (chat langsung dengan penjual).

**Kompetitor tidak langsung:**
- Brand skincare lokal lain yang berjualan via Instagram/Shopee/TikTok Shop (misalnya brand-brand UMKM skincare sejenis).
- Marketplace besar (Shopee, Tokopedia) yang menawarkan varian produk lebih luas dengan sistem pembayaran terintegrasi.

**Keunggulan kompetitif Nazwa Skincare:**
- Proses checkout langsung terhubung ke WhatsApp pemilik → membangun kedekatan personal dengan pelanggan.
- Tidak tergantung platform pihak ketiga (marketplace), sehingga margin lebih besar dan data pelanggan dimiliki sendiri.
- Tampilan web yang lebih premium dibanding katalog WhatsApp/Instagram biasa.

## 4. Strategi Manajemen Produk & Katalog

**Struktur kategori produk:**
| Kategori | Contoh Produk |
|---|---|
| Facial Care | Facial Wash, Moisturizer, Toner |
| Serum | Hyaluronic Serum, Serum Vitamin C |
| Lip Care | Lip Balm |
| Masker | Sheet Mask, Face Mask |
| Body Care | Body Lotion, Body Scrub |

**Strategi katalog:**
- Setiap produk memiliki nama, deskripsi singkat yang persuasif (contoh: *"Cerahkan & proteksi antioksidan"*), harga, kategori, dan label penanda (**Terlaris**, **Baru**, **Promo**, **Unggulan**) untuk memandu keputusan beli.
- Ilustrasi produk menggunakan visual vektor bertema pastel agar konsisten dengan identitas brand tanpa bergantung pada foto produk asli.
- Fitur pencarian (search bar) dan filter kategori memudahkan pelanggan menemukan produk secara instan.
- Rencana pengembangan: menambah varian ukuran, bundling paket (misal "Paket Facial Care Lengkap"), dan rotasi label promosi berdasarkan performa penjualan.

## 5. Model Bisnis & Revenue Stream

- **Model bisnis:** Direct-to-Consumer (D2C) — penjualan langsung dari toko ke konsumen tanpa perantara marketplace.
- **Revenue stream utama:** Penjualan produk skincare per unit (retail).
- **Potensi revenue tambahan (rencana ke depan):**
  - Bundling produk (paket hemat).
  - Program membership/loyalti pelanggan tetap.
  - Reseller/dropship program untuk memperluas distribusi.

## 6. Strategi Harga, Promosi, dan Diskon

**Strategi harga:**
- Harga produk ditetapkan pada rentang terjangkau (Rp 15.000–Rp 65.000) agar mudah diakses target pasar anak muda/mahasiswa.
- Strategi *psychological pricing* sederhana dengan angka bulat (Rp 40.000, Rp 65.000, dst).

**Strategi promosi:**
- Label dinamis pada produk (**Promo**, **Terlaris**, **Baru**, **Unggulan**) untuk menonjolkan item strategis dan mendorong keputusan beli lebih cepat.
- Banner slider di halaman utama untuk highlight promo musiman atau produk andalan.
- Rencana pengembangan: diskon persentase untuk pembelian dalam jumlah tertentu, kode voucher, dan promo hari besar (Ramadan, Harbolnas, dsb).

## 7. Proses Checkout & Simulasi Payment Gateway

**Alur checkout saat ini:**
1. Pelanggan menambahkan produk ke keranjang (cart) — kuantitas dapat diubah atau dihapus.
2. Pelanggan mengisi form data diri: nama, no. HP, alamat, dan (opsional) akun Instagram.
3. Pelanggan memilih salah satu metode pembayaran:
   - **Cash/COD** — bayar saat barang diterima.
   - **QRIS** — menampilkan QR code untuk dipindai lewat GoPay/OVO/DANA/ShopeePay/m-Banking.
   - **SeaBank** — transfer manual ke rekening yang ditampilkan.
   - **DANA** — transfer manual ke nomor e-wallet yang ditampilkan.
4. Sistem membuat nomor invoice otomatis dan menyusun ringkasan pesanan.
5. Pesanan dikirim otomatis ke WhatsApp toko dalam format pesan terstruktur (invoice, tanggal, data pelanggan, rincian item, total, metode bayar).

**Catatan simulasi payment gateway:**
Payment gateway pada sistem ini bersifat **simulasi manual** (QRIS statis & rekening tujuan ditampilkan langsung), belum terintegrasi dengan payment gateway resmi (seperti Midtrans/Xendit/PayPal). 

**Rencana pengembangan ke depan:**
- Integrasi payment gateway resmi (Midtrans/Xendit) agar pembayaran QRIS, VA bank, dan e-wallet dapat diverifikasi otomatis secara real-time.
- Menambahkan status pembayaran otomatis (pending/paid/failed) tanpa perlu verifikasi manual oleh admin via WhatsApp.

## 8. Rencana SEO, Keamanan, dan Pemeliharaan

**SEO:**
- Optimasi `<title>` dan meta description dengan kata kunci relevan (misal: "skincare murah", "toner wajah", "serum vitamin C").
- Menambahkan data terstruktur (schema.org Product) agar produk tampil lebih baik di hasil pencarian Google.
- Membuat konten blog/artikel edukasi skincare untuk meningkatkan trafik organik.
- Pastikan halaman cepat diakses (core web vitals) dan responsif di perangkat mobile.

**Keamanan:**
- Saat ini data pelanggan (nama, no. HP, alamat) hanya dikirim ke WhatsApp toko — perlu dipastikan tidak ada penyimpanan data sensitif di sisi klien.
- Rencana ke depan: enkripsi data saat transaksi (HTTPS wajib), validasi input form untuk mencegah *injection*, serta kebijakan privasi data pelanggan.
- Jika payment gateway resmi diintegrasikan, wajib mengikuti standar keamanan PCI-DSS dari penyedia gateway.

**Pemeliharaan:**
- Update rutin katalog produk (harga, stok, deskripsi).
- Backup berkala data pesanan/pelanggan.
- Monitoring performa website (broken link, kecepatan loading, kompatibilitas browser).

## 9. Rencana Penggunaan Data Analytics untuk Pengambilan Keputusan

- **Analisis produk terlaris:** Melacak produk dengan penjualan/permintaan tertinggi untuk menentukan fokus stok dan promosi.
- **Analisis perilaku pencarian:** Memanfaatkan data dari fitur search untuk mengetahui produk apa yang paling banyak dicari pelanggan, termasuk kata kunci yang tidak menghasilkan produk (peluang produk baru).
- **Analisis funnel checkout:** Mengukur tingkat konversi dari "produk ditambahkan ke keranjang" hingga "pesanan berhasil dikonfirmasi" untuk mengidentifikasi titik drop-off.
- **Analisis metode pembayaran:** Mengetahui metode pembayaran favorit pelanggan untuk menyesuaikan strategi promosi (misal cashback khusus QRIS).
- **Rencana implementasi:** Integrasi Google Analytics/Meta Pixel untuk tracking trafik dan sumber pelanggan, serta dashboard sederhana untuk memantau tren penjualan dari waktu ke waktu.

---

## 📁 Struktur Teknis Singkat

| Aspek | Keterangan |
|---|---|
| Jenis Aplikasi | Single-page web app (HTML/CSS/JavaScript murni) |
| Bahasa | Bahasa Indonesia |
| Font | Cormorant Garamond, Jost, Parisienne (Google Fonts) |
| Fitur utama | Katalog produk, filter kategori, pencarian, keranjang, checkout, simulasi pembayaran, integrasi WhatsApp |
| Kontak pemesanan | WhatsApp otomatis (`wa.me`) |

---

*Dokumen ini merupakan Business Overview yang disusun berdasarkan hasil analisis kode sumber `index.html` Nazwa Skincare, mencakup aspek bisnis yang wajib didokumentasikan.*
