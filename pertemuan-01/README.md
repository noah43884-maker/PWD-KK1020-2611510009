# Pertemuan -1 Dokumentasi pemahaman Konsep Dasar Pemrograman Web
## 1. Konsep Dasar Pemrograman Web
Pemrograman web adalah cara membuat halaman atau aplikasi yang bisa dibuka lewat peramban web (*Web Browser*) melalui jaringan seperti internet. Halaman web umumnya dibagi menjadi web statis yang isinya tetap sama kecuali kode berkasnya diubah secara manual, dan web dinamis yang kontennya dapat berubah mengikuti data, waktu, atau interaksi pengguna.
## 2. Arsitektur Klien-Peladen 
Arsitektur klien-peladen (*client-server*) membagi peran antara *client* dan *server*. 
*Client* (seperti *web browser* di laptop atau ponsel pengguna) bertugas meminta informasi serta menampilkan halaman kepada pengguna, sedangkan *server* bertugas menyimpan berkas aplikasi web, menjalankan proses di sisi peladen, dan mengirimkan hasil yang diminta ke *client*
## 3. Permintaan dan Respons HTTP
Pertukaran data antara *client* dan *server* pada web umumnya menggunakan protokol HTTP. Ketika pengguna membuka alamat web atau mengirim formulir, *client* mengirimkan *HTTP Request* ke *server*, lalu *server*memproses permintaan tersebut dan mengembalikan *HTTP Response* yang membawa data halaman beserta kode status respons, seperti berhasil dimuat atau tidak ditemukan. 
## 4. HTML, CSS, JavaScript, PHP, dan MySQL
* **HTML:** membentuk kerangka struktur dan isi utama halaman web, seperti judul, paragraf, daftar, tautan dan formulir.
* **CSS:** mengatur tampilan visual halaman web, mulai dari warna, jenis huruf, ukuran teks dll
* **JavaScript:** menghadirkan interaktivitas dan logika di sisi *client*, misalnya validasi inptu, mengubah tampilan secara langsung, atau merespons klik pengguna
* **PHP:** bahasa pemrograman sisi *server* yang memproses data, mengatur logika aplikasi, dan menyusun keluaran dinamis sebelum dikirim ke *browser*.
* **MySQL:** sistem manajemen basis data telasional untuk menyimpan, mencari, mengubah dan mengelola data secara terstruktur
## 5. Hubungan Antarteknologis 
Kelima teknologi ini bekerja berkesinambungan dalam membangun aplikasi web modern. Saat pengguna berinteraksi di *browser*, *HTML*, *CSS*, dan *JavaScript* mengatur struktur, tampilan, serta aksi di sisi klien. Ketika data perlu diproses atau disimpan, permintaan dikirim ke *server* untuk diproses oleh *PHP* dan dihubungkan ke basis data *MySQL*, kemudian hasilnya dikirimkan kembali agar bisa dilihat dan digunakan oleh pengguna. 
