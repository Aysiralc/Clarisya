# Aplikasi Setoran BooBank
![BooBank](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjRYGV1jzcK2_-ExmoHt64_ucznbLcDaX68Zc9OvxxkbQgPMM1FFejEIp_QXFvDV8Be75jGHghyLpN6mrTEmmRmiVAqdIPQih0oh5x6C-ROQ75xe-z6K2WDgp6VRAjURVs0FjSZY92csvg1YGMqJ06nf1FGPJzVVhaz2W9D2pt_gGlnbqw1XHgLlz_v/s320/boobank.png)

Aplikasi Setoran BooBank adalah sebuah aplikasi sederhana yang memungkinkan pengguna untuk melakukan setoran tunai ke akun mereka. Aplikasi ini dibangun dengan menggunakan bahasa pemrograman PHP dan HTML.

## Fitur Utama

Aplikasi Setoran BooBank memiliki fitur-fitur berikut:

1. Formulir Setoran: Pengguna dapat mengisi formulir dengan informasi seperti nama lengkap, jenis kelamin, kantor cabang, nomor rekening, dan nominal setoran.
2. Validasi Setoran: Aplikasi melakukan validasi terhadap setoran yang dimasukkan. Setoran harus berupa angka dan minimal Rp100.000.
3. Hitung Biaya Admin: Jika setoran kurang dari Rp1.000.000, aplikasi akan menghitung dan menambahkan biaya admin sebesar Rp5.000.
4. Tampilan Detail Setoran: Setelah setoran berhasil diverifikasi, aplikasi akan menampilkan detail setoran termasuk biaya admin (jika ada) dan total setoran.
5. Penyimpanan Rincian Setoran: Aplikasi menyimpan rincian setoran ke dalam file teks yang dapat digunakan untuk melacak setoran yang telah dilakukan.

## Tech

Aplikasi Setoran BooBank dibangun menggunakan teknologi-teknologi berikut:

- *XAMPP*: Aplikasi XAMPP adalah sebuah software web server yang digunakan untuk mengembangkan dan merancang situs website pada server lokal 
- *HTML*: Untuk membuat struktur halaman web.
- *CSS*: Untuk mengatur tampilan dan gaya visual halaman web.
- *PHP*: Digunakan sebagai bahasa pemrograman server-side untuk memproses data dan mengelola logika bisnis.
- *Sublime Text*: Editor teks sederhana untuk mengembangkan kode aplikasi.
- *Google Chrome*: Aplikasi Google Chrome adalah browser web yang tersedia tanpa biaya yang merupakan tools penting dalam mmebuat sebuah halaman website,dsb.

## Cara Menggunakan Aplikasi

Berikut adalah langkah-langkah untuk menggunakan Aplikasi Setoran BooBank:

1. Buka halaman aplikasi di browser Anda.
2. Isi formulir dengan informasi yang diminta, seperti nama lengkap, jenis kelamin, kantor cabang, nomor rekening, dan nominal setoran.
3. Klik tombol "Submit" untuk mengirimkan data setoran.
4. Jika setoran valid, aplikasi akan menampilkan detail setoran, termasuk biaya admin (jika diperlukan) dan total setoran.
5. Rincian setoran juga akan disimpan dalam file teks sebagai catatan.

Pastikan Anda memasukkan setoran dengan benar dan mengikuti petunjuk yang diberikan oleh aplikasi.

## Persyaratan Sistem

Aplikasi Setoran BooBank membutuhkan lingkungan berikut untuk berjalan:

1. Server web yang mendukung PHP (misalnya Apache).
2. PHP versi baru.

## Struktur
📦aplikasi-setoran-boobank
 ┣ 📂css
 ┃ ┗ 📜style.css
 ┣ 📂images
 ┃ ┗ 📜boobank.png
 ┣ 📜index.php
 ┣ 📜Readme.md
 ┗ 📜rincian_setoran.txt

## Instalasi

Untuk menggunakan Aplikasi Setoran BooBank, ikuti langkah-langkah berikut:

Pindahkan folder aplikasi-setoran-boobank ke dalam folder :
```
c:\xampp\htdocs\
```
 Start apache pada XAMPPP
 
 Akses pada browser dengan url
 ```
 http://localhost/aplikasi-setoran-boobank/
```

## Credit
> Clarisya Adeline
