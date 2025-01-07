# project-uas
## Nama : Althaf Afif Faiz
## NIM : 312410404
## Kelas : TI.24.A.3

### Project UAS membuat program kasir sederhana menggunakan konsep modular dan oop

## Stuktur Program 
### 1. data
### 2. view
### 3. process
### 4. main

## Berikut ini program dari kasir sederhana 
## 1. DATA
![Screenshot 2025-01-06 003624](https://github.com/user-attachments/assets/fb804e05-d401-49e8-9097-95661008897f)

## Penjelasan 
Menyimpan daftar barang yang dibeli dan total harga. _init_: Konstruktor kelas Data, digunakan untuk inisialisasi atribut items (daftar barang yang dibeli) dan total (total harga pembelian).
add_item: Fungsi ini digunakan untuk menambahkan produk ke dalam daftar items dan menghitung subtotal (harga x jumlah) dari produk yang dibeli. Total harga (self.total) juga akan diperbarui setiap kali produk baru ditambahkan.

## 2. VIEW
![image](https://github.com/user-attachments/assets/93b16666-bf93-414f-9f75-2fccda825ebc)

## Penjelasan
Modul ini berisi kelas View, yang bertanggung jawab untuk menampilkan struk belanja setelah transaksi selesai. _init_: Konstruktor kelas View yang menerima objek Data sebagai parameter untuk mengakses informasi transaksi yang telah dilakukan.
display_receipt: Fungsi ini digunakan untuk menampilkan struk belanja dalam format tabel. Tabel ini berisi:   
Nomor urut produk.   
Nama produk.   
Harga per unit produk.   
Jumlah produk yang dibeli.   
Subtotal (harga x jumlah).   
Setelah semua barang ditampilkan, total harga dari semua barang ditampilkan di bagian bawah.

## 3. PROCESS
![code proses](https://github.com/user-attachments/assets/78d3bc9a-c804-4e2b-9f02-cef121566671)

## Penjelasan 
Modul ini berisi kelas Process, yang menangani logika transaksi dan pengolahan input pengguna. _init_: Konstruktor kelas Process yang menerima objek Data dan available_products (daftar produk yang tersedia di toko) sebagai parameter.
process_input: Fungsi ini mengatur alur interaksi dengan pengguna. Pengguna diminta untuk memilih produk dan memasukkan jumlah produk yang ingin dibeli. Jika pengguna memilih produk yang tidak valid atau jumlah produk yang kurang dari 1, maka akan ditampilkan pesan kesalahan dan input ulang diminta.
show_available_products: Fungsi ini menampilkan daftar produk yang tersedia di toko dengan format sejajar (nomor produk, nama produk, dan harga).

## 4. MAIN
![image](https://github.com/user-attachments/assets/06f3f2cf-e8a3-42cd-8b56-616eb921a5c5)

## Penjelasan
File ini adalah file utama yang menghubungkan modul-modul lainnya, menjalankan program dan mengatur alur proses transaksi. main(): Fungsi utama yang menginisialisasi objek dari kelas Data, Process, dan View. Kemudian menjalankan proses transaksi dengan process.process_input() dan menampilkan struk belanja dengan view.display_receipt().

## Alur kerja program
Mulai Program: Program dimulai dengan mengeksekusi fungsi main() yang menginisialisasi produk yang tersedia dan membuat objek-objek dari kelas Data, Process, dan View.   
Menampilkan Produk yang Tersedia: Fungsi show_available_products menampilkan daftar produk yang tersedia dengan nomor, nama, dan harga.   
Meminta Input Pengguna: Pengguna diminta memilih produk dan memasukkan jumlah produk yang ingin dibeli. Proses ini dilakukan berulang-ulang hingga pengguna memilih untuk berhenti.   
Menambahkan Produk ke Keranjang: Setelah memilih produk dan jumlah, produk akan ditambahkan ke dalam Data dan harga total akan diperbarui.   
Menampilkan Struk Belanja: Setelah transaksi selesai, fungsi display_receipt akan menampilkan struk belanja dengan rincian produk yang dibeli, jumlah, harga, dan total yang harus dibayar.   
Selesai: Program selesai setelah struk belanja ditampilkan.   

## Berikut ini link penjelasan program kasir sederhana 
https://youtu.be/CSyzbxRcSZk?si=sILfwbEcGNp5aOc3 



