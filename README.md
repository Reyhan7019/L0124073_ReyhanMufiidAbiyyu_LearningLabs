# JKT48 Unofficial Website

Website ini adalah situs tidak resmi untuk grup idola **JKT48** yang mencakup beberapa halaman dengan informasi tentang konser kelulusan Shani "LAST VOYAGE", produk eksklusif merchandise, dan fitur untuk pengunjung memberikan umpan balik (feedback). 

Website ini terdiri dari tiga halaman utama:
1. **Home Page** - Menampilkan informasi terkait konser Shani dan perjalanan karirnya di JKT48.
2. **Product Page** - Menampilkan daftar produk eksklusif yang dijual dalam rangka konser kelulusan Shani.
3. **Feedback Page** - Halaman untuk pengunjung memberikan kritik, saran, atau umpan balik lainnya.

## Fitur

- **Home Page**: Menyediakan informasi umum tentang Shani dan konser kelulusannya.
- **Product Page**: Daftar produk merchandise eksklusif dengan gambar dan harga.
- **Feedback Page**: Formulir bagi pengunjung untuk mengirimkan kritik dan saran melalui email.
- **Desain Responsif**: Tampilan yang responsif dan dapat disesuaikan di berbagai perangkat.

## Struktur Proyek

Berikut adalah struktur folder dan file dalam proyek ini:
```
katalog-project/  
│  
├── index.html  
├── content.html  
├── feedback.html  
│  
├── css/  
│ └── style.css  
│  
├── images/  
│ ├── logo.svg  
│ ├── content_1.jpg  
│ ├── content_2.jpg  
│ ├── content_3.jpg  
│ ├── content_4.jpg  
│ ├── content_5.jpg  
│ └── content_6.jpg  
│  
├── js/  
│ └── script.js  
└── README.md
```
### Halaman-halaman

1. **`index.html` (Home Page)**:  
   Halaman utama yang menyambut pengunjung dengan informasi tentang Shani, termasuk konser kelulusan "LAST VOYAGE". Dilengkapi dengan menu navigasi ke halaman lain dan tombol untuk melihat produk atau memberikan umpan balik.

2. **`content.html` (Product Page)**:  
   Halaman yang menampilkan merchandise eksklusif yang dijual untuk konser Shani, termasuk gambar produk, nama produk, dan harga. Pengunjung juga diberikan link untuk membeli produk melalui platform e-commerce seperti Tokopedia dan Shopee.

3. **`feedback.html` (Feedback Page)**:  
   Halaman formulir umpan balik yang memungkinkan pengunjung untuk mengirimkan kritik, saran, atau umpan balik melalui email. Formulir ini juga menampilkan sebuah notifikasi setelah pengunjung mengirimkan umpan balik mereka.

### File CSS

- **`style.css`**:  
  File ini mengatur desain dan layout dari seluruh halaman, termasuk:
  - Tata letak header dan footer.
  - Desain menu navigasi yang responsif.
  - Styling untuk tombol, tabel produk, dan formulir feedback.

### File JavaScript

- **`script.js`**:  
  File ini berisi fungsi JavaScript sederhana untuk menampilkan notifikasi ketika pengunjung mengirimkan umpan balik di halaman **Feedback**. Fungsi `notif()` akan memunculkan pesan konfirmasi bahwa feedback telah terkirim.

```javascript
function notif() {
    alert("Feedback Telah Terkirim. Terimakasih!");
}
```

## Cara Menjalankan

1. Clone atau Unduh Proyek
Anda bisa meng-clone atau mengunduh proyek ini dengan menggunakan perintah berikut di terminal:  
`git clone <URL_REPOSITORI>`

2. Buka File HTML di Browser  
Setelah mengunduh proyek, buka file index.html di browser untuk melihat situs. Anda dapat membuka file HTML lainnya untuk mengakses halaman produk atau umpan balik.

3. Pastikan Semua Folder dan File Tersedia  
Pastikan semua folder gambar `(images/)`, `stylesheet (css/)`, dan `JavaScript (js/)` sudah lengkap agar halaman dapat ditampilkan dengan baik

## Penggunaan

Home Page: Menyediakan informasi tentang konser kelulusan Shani dan perjalanan karirnya bersama JKT48.  
Product Page: Menampilkan produk-produk eksklusif yang tersedia untuk dijual, termasuk gambar dan harga produk.  
Feedback Page: Mengumpulkan umpan balik dari pengunjung mengenai situs atau acara.  

## Kebutuhan

Web browser (Chrome, Firefox, Safari, dll.)  
Koneksi internet (untuk membuka link ke Tokopedia dan Shopee)

## Pengembang

Reyhan Mufiid Abiyyu  
Learning Labs 2024

## Lisensi

Proyek ini dilisensikan di bawah MIT License. Lihat file LICENSE untuk informasi lebih lanjut.
