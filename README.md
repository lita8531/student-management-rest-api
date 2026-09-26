# Student Management REST API

Student Management REST API adalah aplikasi untuk mengelola data siswa menggunakan Node.js, Express.js, dan MySQL.

## Fitur

- Menampilkan daftar siswa
- Menampilkan detail siswa
- Menambahkan siswa
- Mengubah data siswa
- Menghapus siswa
- Loading data
- Pesan sukses dan error
- Konfirmasi sebelum menghapus
- Menampilkan response API pada halaman

## Teknologi

- Node.js
- Express.js
- MySQL
- HTML
- CSS
- JavaScript

## REST API

| Method | Endpoint | Fungsi |
|---|---|---|
| GET | `/api/siswa` | Menampilkan semua siswa |
| GET | `/api/siswa/:id` | Menampilkan siswa berdasarkan ID |
| POST | `/api/siswa` | Menambahkan siswa |
| PUT | `/api/siswa/:id` | Mengubah data siswa |
| DELETE | `/api/siswa/:id` | Menghapus siswa |

## Cara Menjalankan

Install dependency:

```bash
npm install