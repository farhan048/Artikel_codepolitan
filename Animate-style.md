# Buat website kamu lebih menarik dengan animate.style

Hi Coders! Kali ini kita akan membahas animate.css atau animate. Oke, langsung saja kita bahas.
Animate.css atau Animatae.style merupakan sebuah library CSS3 yang dibuat oleh Dan Eden untuk mempermudah developer dalam membuat animasi pada element html tanpa harus membuatnya dari awal karena sudah disiapkan oleh animate.css. Fitur animate.css ini saya cukup sudah lumayan lengkap dari animasi masuk(in) sampai animasi keluar (out), cara penggunaan animate.css sangatlah mudah kita hanya perlu menambahkan class animasi yang ada pada animate.css ke element html yang ingin kita beri efek animasi. 

Nah untuk memakai animate. Ada beberapa step yang mesti dilakukan

1. Kita perlu library animate.css nya dulu, bisa kita instal pada laptop kita atau bisa secara CDN, nah kali ini kita akan menggunakan CDN karena lebih mudah dan praktis, Link Untuk mengakes Animate.style [Klik Disini](https://animate.style/)
2. Buka file index.html atau file utama pada web kita yang berisi full body html.
3. Pada tag `<head>` tambahkan baris kode berikut untuk memanggil file animate.css kedalam website kamu.
  
```
  <head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
 ```
4. . Cari element yang akan diberikan animasi, untuk contoh saya buat sebuah element html dengan text “An animated element”.
   
```
<h1 class="animate__animated animate__fadeInLeft">An animated element</h1>
```

5. Simpan dan jalankan pada browser, elemen diatas akan menghasilkan efek animasi fadeIn.

## Cara Penggunaan

Pada dasarnya cara penggunaan animate.css ini sangat mudah, cukup tambahkan class css yang telah disediakan oleh animate.css pada element html yang akan kita berikan efek animasi. Sebagai contoh:

`animate__animated` adalah class yang mesti ditambahkan kedalam elemen yang akan di beri animasi.

`animate__bounce` adalah nama dari efek animasi yang diberikan yaitu bounce, oh iya untuk memanggil nama dari animasi jangan lupa tambahkan `animate_` sebagai prefix.

`<h1 class="animate__animated animate__bounce">Hello Word</h1>`

 Nah dengan animate.css atau animate style kita dapat membuat lebih menarik website kita agar tidak monoton dan pengujung website lebih tertarik terhadap website kita.
