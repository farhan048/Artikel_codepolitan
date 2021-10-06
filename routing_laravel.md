# Belajar Routing laravel

## Pengertian Routing
Routing sendiri adalah proses pengiriman data maupun informasi ke pengguna melalui sebuah permintaan yang dilakukan kepada alamat yang sudah terdaftar, lalu alamat tersebut akan memproses dari permintaan kita tadi. Setelah proses selesai maka akan mengembalikan sebuah output atau hasil dari proses tersebut.

Di dalam folder project laravel kita, disana terdapat folder routes. Dimana terdapat 4 file yaitu api.php, channels.php, console.php, web.php . Dari ke empat file ini memiliki fungsi masing-masing .. yaitu :
- api.php : File ini digunakan untuk membuat routing API. Yapz, di dalam file ini kita juga dapat membuat core service API dengan menggunakan Laravel.
- channels.php : File ini digunakan untuk membuat routing yang bersifat broadcasting event, seperti notification.
- console.php : File ini digunakan untuk membuat routing command yang berjalan di terminal. Jadi kita juga bisa membuat perintah artisan kita sendiri.
- web.php : File ini digunakan untuk membuat routing web biasa.

## Jenis - jenis method Routing Laravel
Ada 6 jenis method yang bisa digunakan pada route Laravel untuk merespon HTTP verb, antara lain :
- Route::get($uri, $callback);
- Route::post($uri, $callback);
- Route::put($uri, $callback);
- Route::patch($uri, $callback);
- Route::delete($uri, $callback);
- Route::options($uri, $callback);

## CSRF Protection
Setiap form html yang mengarah ke route POST, PUT, PATCH, atau DELETE yang ditentukan dalam file route web harus menyertakan token CSRF. Jika tidak, permintaan akan ditolak.
```
<form method="POST" action="/profile">
    @csrf
    ...
</form>
```