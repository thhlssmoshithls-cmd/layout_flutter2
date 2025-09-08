Langkah - langkah praltikum :
1. import 'package:flutter/material.dart';Digunakan agar kita bisa memakai widget bawaan Flutter (misalnya Scaffold, AppBar, Text, Row, Column, dll).
2. Fungsi main() adalah titik awal program Dart/Flutter.runApp() menjalankan aplikasi Flutter dan memanggil widget utama (MyApp).
3.  Pada Kelas MyApp StatelessWidget: widget yang tidak berubah (static). MaterialApp: membungkus aplikasi dengan tema Material Design. title: judul aplikasi. theme: warna utama aplikasi. home: halaman utama → diarahkan ke MyHomePage().
4. Kelas MyHomePage Juga StatelessWidget. Di dalamnya kita susun layout halaman utama aplikasi.
5. Pada bagian Judul Container: memberi padding (ruang dalam). Row: menyusun widget secara horizontal. Expanded: agar teks menyesuaikan lebar. Column: menampilkan teks secara vertikal. Icon + Text("41"): menampilkan bintang merah dengan jumlah rating.
6. Pada bagian tombol Fungsi untuk membuat tombol icon + teks. Dipakai agar kode lebih singkat (tinggal panggil dengan icon & label). Row: menampilkan tombol secara horizontal.
7. Pada bagian teks Padding: memberi jarak di sekeliling teks. Text: menampilkan deskripsi pantai softWrap: true: teks otomatis pindah baris kalau terlalu panjang.
8. Pada tampilan Utama Scaffold: kerangka utama halaman (ada AppBar dan body). AppBar: menampilkan judul aplikasi. ListView: agar halaman bisa scroll ke bawah. Isi ListView:Gambar pantai (Image.asset). Bagian Judul (titleSection). Bagian Tombol (buttonSection). Bagian Teks (textSection).

 