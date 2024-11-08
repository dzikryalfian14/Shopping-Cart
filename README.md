# Shopping-Cart
Proyek ini adalah aplikasi Shopping Cart yang dibangun menggunakan teknologi MongoDB, Vue.js, Express.js, dan Node.js. Aplikasi ini terdiri dari dua bagian utama: client untuk antarmuka pengguna dan server untuk API backend.

# Struktur Proyek
shopping-cart/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── views/
│   │   ├── App.vue
│   │   ├── main.js
│   └── package.json
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── package.json
└── README.md

# Persyaratan
Node.js
MongoDB

Instalasi

## Persyaratan
1. Node.js
2. MongoDB

## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/shopping-cart.git
   cd shopping-cart
2. Instal dependensi untuk client:
   ```bash
   cd ../client
   npm install
3. Instal dependensi untuk server:
   ```bash
   cd ../server
   npm install

## Menjalankan Aplikasi 
1. Install MongoDB
2. Jalankan Server
    ```bash
    cd ../server
    nodemon app.js
4. Jalankan Client Front End
    ```bash
      cd ../client
     npm run serve

Fitur
- Menambahkan Produk ke Keranjang: Pengguna dapat menambahkan produk ke keranjang belanja.
- Menghapus Produk dari Keranjang: Pengguna dapat menghapus produk dari keranjang belanja.
- Melihat Total Harga: Pengguna dapat melihat total harga dari semua produk di keranjang belanja.
- Checkout: Pengguna dapat melakukan checkout untuk menyelesaikan pembelian.

Teknologi yang Digunakan
- Frontend: Vue.js
- Backend: Node.js, Express.js
- Database: MongoDB
- HTTP Client: Axios
