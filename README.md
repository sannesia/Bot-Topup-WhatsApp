# Bot Topup WhatsApp Otomatis

**Bot Topup Otomatis** adalah sebuah bot Telegram yang memungkinkan pengguna melakukan transaksi top-up langsung di dalam Telegram dengan mengintegrasikan [API JF Store](https://topup.j-f.cloud/api/docs). Bot ini mempermudah transaksi pembelian produk seperti kredit game mobile, saldo prabayar, dan lainnya.

## Fitur

- **Pemesanan Produk**: Pesan berbagai produk digital seperti kredit game, top-up pulsa, dll.
- **Cek Saldo Secara Real-time**: Memeriksa saldo secara otomatis dan memberikan notifikasi jika saldo tidak mencukupi.
- **Status Transaksi**: Memantau dan melacak status pesanan langsung melalui bot.
- **Registrasi Pengguna**: Registrasi sederhana dan harga berbasis peran sesuai dengan tingkatan pengguna (Bronze, Gold, Platinum, VIP).
- **Dan masih banyak lagi.**

## Integrasi dengan [JF Store](https://topup.j-f.cloud)

Bot ini terintegrasi dengan layanan JF STORE, memungkinkan pengguna untuk berinteraksi dengan layanan top-up yang ditawarkan oleh [JF Store](https://topup.j-f.cloud). Integrasi ini mencakup:

- **Mengambil Informasi Profile**.
- **Mengambil Informasi Produk**: Mendapatkan produk top-up yang tersedia beserta harganya.
- **Mengirim Pesanan**: Mengirim pesanan produk digital melalui API JF Topup.
- **Memantau Status Pesanan**: Menanyakan dan menampilkan status dari setiap transaksi.

## Memulai

### Prasyarat

Sebelum menyiapkan bot, pastikan Anda memiliki:

- [Node.js](https://nodejs.org/) yang sudah terinstall
- Nomor WhatsApp untuk bot
- Akun [JF Store](https://topup.j-f.cloud/api/docs) dan APIKEY Anda
- **Alamat IP Anda harus di-whitelist** agar bot dapat beroperasi. Pastikan IP Anda sudah ditambahkan ke daftar yang diizinkan untuk mencegah akses yang tidak sah.
  [Klik di sini untuk menambahkan IP Anda](https://wa.me/6285773305337?text=Halo,+mau+add+ip)

### TUTORIAL BIKIN DATABASE MONGODB
[Klik disini](https://www.youtube.com/watch?v=JtRUihD-TP4)

### Instalasi

1. **Klon repositori**:
   ```bash
   git clone https://github.com/ferianss/Bot-Topup-WhatsApp.git

2. **cd Bot-Topup-WhatsApp**
3. **Install the dependencies:**
   ```
   npm install
4. **Edit the config.js file in folder db**
5. **Run the bot:**
   ```
   node index.js
6. Untuk menampilkan harga produk silahkan command 'Setprofit' 

**All credits to JF Dev.**
