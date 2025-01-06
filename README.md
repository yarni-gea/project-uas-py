# project-uas-py

# nama : yarni gea 

# nim : 312410413

# kelas : TI.24.A3 

## struktur program 

# 1. class data 

menyinpan informasi tentang data buku 

Atribut:

title: Judul buku

author: Pengarang buku

year: Tahun terbi

Metode:

    __init__(self, title, author, year): Konstruktor untuk inisialisasi atribut

 # 2. Class  View

 Mengelola input/output dari pengguna:

 Metode:
 
             dispalay_ menu(): menampilkan menu utama 

             geet_book_input(): meminta data buku dengan validasi

             display_book(books)(): menampilkan data buku dalam bentuk tabel

# 3. Class BookManager

Mengelola daftar buku:

# atribut: 

            books: daftar buku yang disimpna 

# metode: 

        add_book(title, author, year):menambahkan buku ke daftar 

        get_all_books(): mengembalikan semua data buku yang di simpan 

# 4. Class Main

# atribut: 

            manager: Objek dari class BookManager.

            view: Objek dari class View.

# metode: 

        run(): Menjalankan program dalam loop hingga pengguna keluar.

# Validasi Input: 

Judul Buku: Tidak boleh kosong.

Pengarang Buku: Tidak boleh kosong.

Tahun Terbit: Harus berupa bilangan bulat positif.

# Cara Menjalankan

1. simpan file dangan nama book_maneger.py.

2. Jalankan program di terminal/command prompt

        python book_manager.py.

# Contoh Penggunaan

# menambahkan buku 

        === Sistem Pengelolaan Buku ===

        1.Tambah Buku

        2.Tampilkan Data Buku 

        3. keluar 

        Pilih menu (1-3): 1
        
        Masukkan judul buku: Pemrograman Python
        
        Masukkan pengarang buku: Guido van Rossum
        
        Masukkan tahun terbit buku: 2020
        
        Buku berhasil ditambahkan!

# menampilkan data buku 

            == Data Buku ===
No.  Judul                         Pengarang           Tahun     
----------------------------------------------------------------------
1    Pemrograman Python            Guido van Rossum    2023     

# Mengakhiri Program

      === Sistem Pengelolaan Buku ===
      
        1.Tambah Buku 

        2. Tampilkan Data buku 

        3.keluar 

        Pilih menu (1-3): 3

        Terima kasih telah menggunakan program ini!


        









            
            

 

