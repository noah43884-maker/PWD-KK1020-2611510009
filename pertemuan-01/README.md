# Pertemuan 1 - Pemrograman Web Dasar
## 1. Konsep Dasar Pemrograman Web
Menurut pemahaman saya, Pemrograman Web adalah proses merancang, membangun, dan mengelola aplikasi atau situs web yang dapat diakses melalui peramban web (*web browser*) menggunakan jaringan komputer dan protokol komunikasi seperti HTTP atau HTTPS. Dalam pemrograman web, halaman dapat bersifat statis (isinya tetap hingga berkas diperbarui) maupun dinamis (isinya dapat berubah sesuai input pengguna, waktu, data dari basis data).

## 2. Arsitektur Klien-Peladen
Menurut pemahaman saya, Arsitektur *client-server* membagi tugas dalam sistem web menjadi dua bagian utama:
- **Klien (*Client*)**: Perangkat atau aplikasi (umumnya *web browser*) yang mengirimkan permintaan layanan/data dan menampilkan hasilnya kepada pengguna.
- **Peladen (*Server*)**: Komputer atau layanan yang menerima permintaan dari klien, memproses logika atau mengambil data yang dibutuhkan, lalu mengirimkan kembali hasilnya.

## 3. HTTP Request dan HTTP Response
Menurut pemahaman saya, Komunikasi antara *browser* dan *server* web berjalan melalui siklus permintaan dan balasan protokol HTTP:
- **HTTP Request**: Pesan yang dikirim klien ke *server* untuk meminta sumber daya atau mengirim data. Komponen utamanya meliputi *method* (seperti `GET` untuk mengambil data dan `POST` untuk mengirim data),  alamat URL/*path*, *header* (informasi tambahan seperti tipe konten atau autentikasi), serta *body* (isi data yang dikirim, misalnya saat mengisi formulir).
- **HTTP Response**: Pesan balasan dari *server* kepada klien setelah memproses *request*. Isinya mencakup *status code* (seperti `200 OK` untuk berhasil, `404 Not Found` untuk halaman tidak ditemukan, atau `500 Internal Server Error` untuk gangguan di *server*), *header*, daan *body* yang memuat konten balasan ( misalnya halaman HTML atau data JSON).

## 4. html, css, JavaScript, PHP dan MySQL
Menurut pemahaman saya kelima teknologi ini memiliki peran yang saling melengkapi dalam pengembangan aplikasi web:
- **HTML (*HyperText Markup Language*)**: Bahasa markah standar untuk menyusun struktur dan konten dasar halaman web (seperti judul, paragraf, tautan, gambar, dan formulir).
- **CSS (*Cascading Style Sheets*)**: Bahasa yang mengatur tampilan visual halaman web, seperti tata letak, warna, ukuran huruf, spasi, dan responsivitas di berbagai ukuran layar.
- **JavaScript**: Bahasa pemrograman yang berjalan terutama di sisi klien (*browser*) untuk membuat halaman web menjadi interaktif, dinamis, serta mampu memvalidasi input atau memperbarui tampilan tanpa memuat ulang seluruh halaman.
- **PHP**: Bahasa pemrograman sisi server (*server-side*) yang dijalankan di *server* web untuk memproses logika aplikasi, menangani data formulir atau sesi pengguna, berinteraksi dengan basis data, dan menghasilkan keluaran dinamis sebelum dikirim ke *browser*.
- **MySQL**: Sistem manajemen basis data relasional (*Relational Database Management System* / RDBMS) yang digunakan untuk menyimpan, menyusun, mencari dan mengelola data secara terstruktur dalam bentuk tabel.

## 5. Hubungan Antarteknologi
Menurut pemahaman saya, saat pengguna membuka situs web, *browser* menampilkan struktur dengan **HTML**, menatanya dengan **CSS**, dan menjalankan interaksi awal dengan **JavaScript**. Ketika data perlu diambil atau disimpan, *browser* mengirimkan **HTTP Request** ke *server*. Di sisi *server*, **PHP** memproses permintaan tersebut dan berkomunikasi dengan *MySQL** untuk membaca atau menulis data. Setelah proses selesai, *server* mengirimkan **HTTP Response** kembali ke *browser* agar hasilnya dapat dilihat oleh pengguna.