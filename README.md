# LATIHAN1DPBO2023

/Saya Muhammad Rizki 2107922 mengerjakan Latihan 1 dalam mata kuliah Desain dan Pmerograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin/

## Deskripsi
Tugas terdiri dari program berbasis OOP menggunakan bahasa pemrograman C++, Java, Python, dan PHP yang menampilkan informasi daftar mahasiswa (sekumpulan objek mahasiswa) dan memiliki fitur menambah, mengubah, dan menghapus data. Setiap mahasiswa memiliki data nama, NIM, program studi, fakultas, dan foto profil (khusus bahasa PHP).

## Desain
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
  
## Penjelasan Singkat Main
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
  
  ## Hasil
  ### Java/C++/Python(kurang lebih sama)
  ![Screenshot (564)m](https://user-images.githubusercontent.com/100481579/219070773-241d2294-e022-43d9-9528-dcccbf95f781.png)
  ![Screenshot (565)m](https://user-images.githubusercontent.com/100481579/219071203-0e3b99d8-70e0-451b-a62d-1e0e205cd167.png)
  ![Screenshot (566)m](https://user-images.githubusercontent.com/100481579/219071223-3c7e7ddd-5314-46a7-85a3-2a5577b60e86.png)
  ![Screenshot (567)](https://user-images.githubusercontent.com/100481579/219071273-fd5367dc-7bf2-47e8-9c35-240cbdc6a0b8.png)

  ### PHP
  #### tampilan awal
  ![Tampilan Awal](https://user-images.githubusercontent.com/100481579/219071766-fcbe2f20-f25e-489a-b0e3-98ce9e2af184.png)
  #### tambah data
  ![Isi form tambah data](https://user-images.githubusercontent.com/100481579/219072002-8371be82-dd5e-4263-ae97-54101b42dd78.png)
  #### Hasil
  ![Hasil setelah tambah data](https://user-images.githubusercontent.com/100481579/219072073-37a67aaa-98a5-4442-aa84-82f909289a78.png)

  
  
