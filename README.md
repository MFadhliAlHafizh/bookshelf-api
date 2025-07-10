# Bookshelf API

Bookshelf API adalah RESTful API sederhana yang dibuat menggunakan [Hapi.js](https://hapi.dev/) untuk mengelola koleksi buku. Proyek ini merupakan bagian dari submission akhir dalam kelas Belajar Membuat Aplikasi Back-End untuk Pemula oleh Dicoding.

## 🚀 Fitur

- Menambahkan buku baru ke rak
- Mengambil semua daftar buku
- Mengambil detail buku berdasarkan ID
- Memperbarui data buku berdasarkan ID
- Menghapus buku berdasarkan ID
- Validasi input untuk nama buku dan jumlah halaman

## 📁 Struktur Proyek
```
BOOKSHELFAPI/
├── src/
│   ├── bookshelf.js
│   ├── handler.js
│   ├── routes.js
│   └── server.js
├── bookshelf-api-test.postman_collection.json
├── bookshelf-api-test.postman_environment.json
├── eslint.config.mjs
├── package-lock.json
└── package.json
```

## 🛠️ Instalasi & Menjalankan Proyek

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan proyek ini di lingkungan lokal:

1. **Clone repositori**
   Salin repositori ini ke komputer kamu menggunakan perintah berikut:
   ```bash
   git clone https://github.com/MFadhliAlHafizh/bookshelf-api.git

2. **Install dependencies**
   Setelah berada di folder proyek, jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:
   ```
   npm install
   ```

4. **Menjalankan server**
   Tersedia dua opsi untuk menjalankan server:
   - Mode produksi (sekali jalan, tidak otomatis restart saat ada perubahan):
   ```
    npm start
   ```
   - Mode pengembangan (menggunakan nodemon, akan otomatis merestart jika ada perubahan pada file):
   ```
    npm run start-dev
   ```
   
5. **Akses API**
   Setelah server berjalan, kamu bisa mengakses API melalui URL:
   http://localhost:9000
