# LATIHAN1DPBO2023

/Saya Muhammad Rizki 2107922 mengerjakan Latihan 1 dalam mata kuliah Desain dan Pmerograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin/

##Deskripsi
Tugas terdiri dari program berbasis OOP menggunakan bahasa pemrograman C++, Java, Python, dan PHP yang menampilkan informasi daftar mahasiswa (sekumpulan objek mahasiswa) dan memiliki fitur menambah, mengubah, dan menghapus data. Setiap mahasiswa memiliki data nama, NIM, program studi, fakultas, dan foto profil (khusus bahasa PHP).

##Desain
terdapat dua kelas yang dipakai pada program ini, yaitu:
1. Class Mahasiswa
  untuk membuat objek mahasiswa, class ini memiliki atribut sebagai berikut:
  -Nama
  -Nim
  -Prodi
  -Fakultas
  dan untuk method sendiri hanya terdiri dari method seperti get dan set untuk masing-masing atribut
2. Class Tabel 
  untuk membuat objek tabel, class ini memiliki atribut sebagai berikut:
  -baris
  -kolom
  selain dari method get dan set terdapat satu method tambahan, yaitu method tampil baris. method ini berfungsi untuk menampilkan satu baris data objek yang dikemas dalam bentuk tabel
  
  Catatan: pada bagian PHP hanya memakain class Mahasiswa saja, karna untuk membuat tabel pada PHP dapat menggunakan tag <table> dari html
  
##Penjelasan Singkat Main
untuk proses awal yaitu deklarasi variabel, array, dan list yang diperlukan
masuk ke bagian loopinh untuk pilih menu, program akan keluar dari loop jika user memilik menu "Keluar"
terdapat 4 fitur utama yaitu:
  1. Tambah Data Mahasiswa
     -minta inputan jumlah data 
     -looping sembari meminta inputan atribut untuk objek
     - objek kemudian ditambahkan ke list of objek daftar mahasiswa
  2. Tampil Daftar
     -menampilkan data objek dalam format tabel dengan objek tabel
  3. Ubah Data Mahasiswa
     -mengubah data berdasarkan nim yang diinputkan, jika nim tidak ditemukan maka update tidak bisa dilanjutakan
  4. Hapus Data Mahasiswa
     -menghapus data berdasarkan nim yang diinputkan, jika nim tidak ditemukan maka delete tidak bisa dilanjutakan
     
  Catatan: pada bagian PHP hanya terdapat bagian tambah dan tampil data saja
  
