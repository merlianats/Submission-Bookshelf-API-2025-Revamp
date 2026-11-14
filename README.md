# Bookshelf API

RESTful API untuk mengelola koleksi buku menggunakan Node.js.

## Installation

Clone repository terlebih dahulu, kemudian masuk ke direktori project.

```bash
npm install
```

## Run Application

Jalankan server dengan perintah:

```bash
npm run start
```

Server akan berjalan sesuai konfigurasi port pada aplikasi.

## API Testing

Pengujian API dilakukan menggunakan **Postman** dengan Collection dan Environment yang telah disediakan di dalam folder project.

1. Buka aplikasi Postman.
2. Import file Collection dan Environment yang tersedia pada folder pengujian.
3. Pilih Environment yang telah di-import.
4. Jalankan server Bookshelf API.
5. Buka Collection yang telah di-import, kemudian jalankan request untuk melakukan pengujian setiap endpoint.
6. Periksa hasil response dan status code untuk memastikan API berjalan sesuai harapan.

## Tech Stack

- Node.js
- Hapi.js
- nanoid
- Postman
