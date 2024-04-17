# LaraPos (toko by tulS)
[![Stable Laravel](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)

## About
Aplikasi pencatatan penjualan toko sederhana dibuat dengan Laravel 7.

## Tugas pengkodean dan Pemograman
nama: Talitha Ulayya isnadiya

Nim: 12030122140304

Kelas: E

## Sumber github
https://github.com/rafipriatna/LaraPOS

### Screenshot tampilan lama

![
![Screenshot transaksi](transaksi.png)

## Screenshot tampilan baru
![image](https://github.com/TalithaUlayya/PengkodeanDanPemrograman-Sistem-Penjualan-Baju/blob/main/Screenshot%20(718).png)

## ERD
![image](https://github.com/TalithaUlayya/PengkodeanDanPemrograman-Sistem-Penjualan-Baju/blob/main/ERD.png)

## Installasi
```
git clone https://github.com/rafipriatna/LaraPos
cd LaraPos
composer install
```
Buat database baru, lalu rename `.env.example` menjadi `.env`, lalu edit:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```
Edit sesuai dengan informasi database yang sudah dibuat.
Setelah itu, lakukan migrasi.
```
php artisan migrate
```
Silakan lakukan register akun di `http://localhost:8000/register`. Secara bawaan, rolenya adalah 'user', untuk mengubahnya
menjadi admin, maka perlu edit manual di table users.

## Lisensi
[MIT license](https://opensource.org/licenses/MIT)
