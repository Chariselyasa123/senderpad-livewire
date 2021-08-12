## Initial setup

Setelah melakukan clone jalankan perintah berikut :

1. Buka aplikasi folder menggunakan perintah `cd` pada cmd atau terminal.
2. Jalankan `composer install` di cmd atau terminal.
3. Buat file `.env` kemudian salin isi dari file `.env.example` ke dalam file `.env` tadi. atau bisa juga dengan menggunakan command promt Windows dengan mengetik `copy .env.example .env`, bila menggunakan Ubuntu `cp .env.example .env`.
4. Buka file `.env` dan ubah nama database (`DB_DATABASE`) menjadi apa pun yang kalian miliki, username (`DB_USERNAME`) dan password (`DB_PASSWORD`) sesuai dengan konfigurasi kalian. Secara default, username adalah root dan kalian dapat membiarkan password kosong. (**Ini untuk Xampp**)
5. Run `php artisan key:generate`
6. Run `php artisan migrate`
7. Run `npm run dev`
8. Run `php artisan serve`
9. Pergi ke [localhost:8000](http://localhost:8000)
