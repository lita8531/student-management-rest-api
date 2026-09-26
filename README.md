# Student Management REST API

## 1. Nama Aplikasi

Student Management REST API

## 2. Deskripsi Aplikasi

Student Management REST API adalah aplikasi untuk mengelola data siswa menggunakan REST API dengan Node.js, Express.js, dan MySQL.

Aplikasi ini memiliki fitur untuk menampilkan, menambahkan, mengubah, dan menghapus data siswa.

## 3. Teknologi yang Digunakan

- Node.js
- Express.js
- MySQL
- HTML
- CSS
- JavaScript
- Git & GitHub

## 4. Cara Menjalankan Backend

1. Pastikan Node.js dan MySQL sudah terinstall.
2. Buka folder project menggunakan VS Code.
3. Buka terminal pada folder project.
4. Install dependency dengan perintah:

```bash
npm install

## Struktur Project

student_management_Rest_Api/
├── config/
│   └── database.js          # Konfigurasi dan koneksi ke database MySQL
├── routes/                  # Folder untuk routing REST API
├── fublic/                  # Folder frontend
│   └── index.html           # Halaman utama aplikasi
├── node_modules/            # Folder dependensi Node.js
├── image.png                # Screenshot frontend
├── getsemua.png             # Screenshot pengujian GET
├── post.png                 # Screenshot pengujian POST
├── put.png                  # Screenshot pengujian PUT
├── delete.png               # Screenshot pengujian DELETE
├── package.json             # Informasi dan dependensi project
├── package-lock.json        # Lock file dependensi
├── README.md                # Dokumentasi project
└── server.js                # File utama server dan REST API