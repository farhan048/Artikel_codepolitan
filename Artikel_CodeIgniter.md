# Apa Yang baru Di CodeIgniter 4 ?
Hai Coders, pasti sudah pada tahu bahwa Codeigniter 4  sudah rilis pada 24 Februari 2020. Pada Codeigniter 4 ini banyak fitur dan perubahan baru yang harus kita ketahui.
## Proses instalasi
Jika dulu pada CI 3 kita mesti menyimpan projectnya pada localhost atau server local kita ( dalam folder htdoc, kita download kemudian kita extract kemudian kita jalankan ).  kalau sekarang kita bisa instal seperti framework modern lainnya dengan menggunakan composser, ini sangat memudahkan karna kita cukup menginstalnya melalui terminal atau git bash saja.
Perintah instal melalui terminal
```composer create-project codeigniter4/appstarter myCI4app```
## Local Server DevelopmentLocal Server Development
Pada update CI 4 ini codeigniter menambahkan fitur local server development sendiri untuk memudahkan dalam pengembangan perangkat lunak. caranya, silakan buka terminal atau command line, kemudian masuk ke folder kerja CodeIgniter yang telah diinstal. Selanjutnya jalankan perintah berikut:
```Php park serve```
Setelah perintah diatas dijalankan, selanjutnya Kita bisa membuka website di URL http://localhost:8080. Dengan Local Development Server ini, Kita bisa membuat website CodeIgniter lebih benar, dan tidak harus di dalam folder htdocs. Menyenangkan bukan?
## Struktur direktori berbeda
CodeIgniter 4 menggunakan struktur directory yang berbeda dari versi sebelumnya. Artinya, tidak memungkinkan bila kita berencana melakukan upgrade CodeIgniter versi lama ke versi yang baru tanpa melakukan coding ulang. Hal ini berbeda dengan versi sebelum-sebelumnya, misalnya ketika Anda menggunakan CodeIgniter 2 dan mau beralih ke versi 3, maka hanya tinggal ditimpa saja.

Di versi 4, semua yang diperlukan dalam membuat aplikasi berada di dalam folder app. Kemudian penamaan file-nya juga sudah menggunakan huruf kapital di bagian depannya.

Di CodeIgniter 4 sudah ada folder public yang didalamnya ada file index.php. Dengan adanya folder public ini membuat aplikasi yang kita buat menjadi lebih aman. Hal ini karena app-nya tidak berada di direktori yang sama dengan folder public sehingga tidak akan kelihatan dari web server-nya.
## Menggunakan PHP Versi 7.2
CodeIgniter 4 mewajibkan untuk menggunakan PHP Versi 7.2 ke atas. Bila web server kita ( XAMPP atau WAMP atau lainnya ) masih menggunakan PHP versi di bawahnya, maka CodeIgniter 4 tidak men-support-nya, jadi jangan lupa update web server kita ya.

Dengan menggunakan PHP versi 7.2 ke atas, akan membuat aplikasi yang Anda buat menjadi lebih cepat sehingga bagus dari segi performance-nya.

## Menggunakan NameSpace
CodeIgniter versi terbaru sudah menggunakan NameSpace, yang sangat membantu bilamana kita bekerja menggunakan library atau script dari pihak ketiga. Meskipun menggunakan nama yang sama tapi NameSpace-nya berbeda, tetap tidak akan menimbulkan masalah.

## AutoLoading Imporvements
Menggunakan standar terbaru psr 4, di mana autoloading-nya bisa menjadi otomatis. Berbeda dengan versi sebelumnya yang harus dilakukan manual.

## Memiliki File .env
File .env adalah file konfigurasi yang akan memudahkan kita dalam pengaturan saat melakukan development, testing, ataupun production menggunakan file environment. 
Manfaat adanya file ini akan sangat terasa saat kita bekerja kolaborasi dalam sebuah tim. Setiap anggota tim, cukup menyimpan file ini ke repository masing-masing tanpa perlu melakukan konfigurasi lagi.

## Memiliki CLI atau Command Line Interface
CodeIgniter 4 saat ini sudah bertransformasi menjadi FrameWork PHP yang modern dengan disertakannya fitur CLI. Fitur ini ada untuk memudahkan para developer dalam membangun aplikasi.

Sebagai contoh, Anda bisa melakukan cronjob dan membuat task interaktif, yang semuanya bisa dilakukan dengan mudah menggunakan Command Line. Sama halnya seperti yang disebutkan di poin 2, server bisa dijalankan melalui terminal. Bahkan Anda juga bisa membuat perintah custom sendiri melalui terminal.  Dengan adanya fitur ini akan memudahkan Anda dalam mengintegrasikan aplikasi yang telah dibuat ke aplikasi lain. 

##  Memiliki Fitur REST
Di dalam CodeIgniter versi terbaru ini, Anda sudah bisa membuat REST API hanya dengan menggunakan CodeIgniter. Di dalamnya sudah ada Resource Route, dimana Anda bisa melakukan routing tidak hanya menggunakan metode yang konvensional seperti Get dan Post, tapi bisa menggunakan metode Restful yang lain seperti Put, Patch, dan Delete.

Mungkin cukup itu saja pembaruan dalam CodeIfniter pada saat artikel ini dibuat. Jika ada pembahasan yang kurang lengkap, silahkan menuju link berikut
