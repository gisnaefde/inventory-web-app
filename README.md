
## Cara Instalasi Project

Pastikan git cli sudah terinstall, kemudian jalankan perintah dibawah
```
1. clone repository
2. copy .env.example rename menjadi .env kemudian atur database di .env
3. composer install
4. php artisan key:generate
5. php artisan migrate --seed
```

## Akun Super Admin
```
email : admin@gmail.com
password : password
```

## Fitur Aplikasi 
- Terdapat 3 role yaitu : super admin, admin, dan customer
- Mengelola Kategori (Super Admin & Admin)
- Mengelola Supplier (Super Admin & Admin)
- Mengelola Barang (Super Admin & Admin)
- Mengelola User (Super Admin & Admin)
- Mengelola Transaksi (Super Admin & Admin)
- Mengelola Roles & Permission (Super Admin)
- Halaman Dashboard dengan berbagai fitur seperti : (Super Admin & Admin) 
   - Barang paling populer
   - Notifikasi permintaan barang yang belum di verifikasi
   - List barang dengan stok kurang dari 10
   - Jumlah Kategori
   - Jumlah Supplier
   - Jumlah Barang
   - Jumlah Kendaraan
   - Jumlah Customer
   - Jumlah Permintaan Barang
   - Jumlah Barang Keluar
   - Jumlah Barang Keluar Bulan Ini
- Permintaan Barang (All Role)
- Peminjaman Kendaraan (All Role)
- Pengembalian Kendaraan (All Role)
- Keranjang (All Role)
- Mengubah Akun (All Role)
- List Transaksi (All Role)
- Search Data
- Responsive

## License
Aplikasi ini bersifat open source dapat digunakan oleh siapa pun dengan syarat tidak untuk di perjual belikan.
