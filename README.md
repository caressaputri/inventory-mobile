1. Perbedaan Stateless widget dan stateful widget adalah stateless widget hanya seperti tempelan gambar saja, jika diklik tidak akan ada perubahan atau notifikasi yang signifikan, sedangkan stateful widget seperti pintu yang jika dibuka dapat menjuju halaman yang berbeda
2. Widget yang saya buat pada tugas 7 aplikasi inventory mobil adalah
   a. MaterialApp: Ini adalah "bos" aplikasi yang mengatur berbagai pengaturan dasar, seperti judul dan tema.
   b. Scaffold: Ini adalah kerangka dasar aplikasi, seperti kertas putih yang siap diisi. Di dalamnya ada bilah atas (AppBar), area isi (body), dan berbagai komponen lain.
   c. AppBar: Ini adalah header di atas aplikasi yang biasanya berisi judul.
   d. SingleChildScrollView: Ini adalah fitur bonus yang membuat isi aplikasi bisa di-scroll, seperti layar perangkat keras. Berguna jika ada banyak hal yang harus ditampilkan.
   e. Padding: Ini adalah bantal atau jarak tambahan untuk elemen-elemen di dalamnya. Digunakan untuk mengatur spasi antar elemen.
   f. Column: Ini adalah pengaturan vertikal, seperti susunan tumpukan kartu.
   g. GridView.count: Ini adalah "kotak-kotak" yang bisa ditata dengan jumlah kolom tertentu.
   h. CardItems: Ini adalah "kotak kartu" kustom yang berisi ikon, teks, dan warna latar belakang.
   i. InkWell: Ini adalah cara fancy untuk menangani ketukan (tap) pada elemen.
   j. Icon: Ini adalah ikon seperti emoji, hanya dalam bentuk widget.
   k. Text: Ini adalah teks yang bisa ditampilkan dalam berbagai gaya.
   l. MyApp (Custom StatelessWidget): Ini adalah root widget dari aplikasi Anda. Ini menginisialisasi dan mengatur konfigurasi dasar aplikasi, termasuk judul, tema, dan halaman beranda.
   m. HomePage (mungkin dari file menu.dart): Ini adalah widget yang mewakili halaman utama aplikasi Anda. Itu akan ditampilkan sebagai halaman pertama ketika aplikasi dijalankan.
3. Cara saya mengimplementasikan step-by-step:
   a. Pertama saya membuat app dengan perintah 'flutter create inventory_mobile'
   b. kedua, saya membuat menu.dart di dalam folder lib yang berisi main.dart
   c. import "import 'package:flutter/material.dart';" dan "import 'package:inventory_mobile/menu.dart';" pada main.dart
   d. import "import 'package:flutter/material.dart';" pada menu.dart
   e. Pada menu.dart membuat widget widget yang diperlukan seperti dijelaskan di atas
   f. Membuka device manager dan memilih divice lalu 'Run" untuk melihat hasilnya atau bisa juga pada root aplikasi tulis perintah "flutter run -d chrome" untuk melihat hasilnya
   g. inisiasi "git init" kemudian "git remote add origin https://github.com/caressaputri/inventory-mobile.git" lalu push aplikasi inventory_mobile ke git pada banch master
   
