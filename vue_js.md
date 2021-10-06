# Pengenalan Konsep Dasar Vuejs untuk Pemula

## Apa itu Vuejs?
<a href="https://ibb.co/DgdbgFN"><img src="https://i.ibb.co/x8Zs8by/Pengertian-vuejs.png" alt="Pengertian-vuejs" border="0"></a>
Vue.js adalah sebuah framework Javascript untuk membuat user interface dan single-page application (SPA).

Vue.js dikenal juga dengan Vue saja dan dieja seperti membaca kata view (/vju:/).

<a href="https://ibb.co/h2BnC78"><img src="https://i.ibb.co/BTy7wzs/Diagram.jpg" alt="Diagram" border="0"></a>
Pada arsitektur MVC (Model–View–Controller), Vuejs hanya akan mengambil peran pada layer View saja.

Yang penting Vue bisa menerima dan mengirim data, lalu membuat tampilan user interface (UI).

Pada dasarnya, fitur utama Vue lebih fokus pada rendering dan komposisi komponen.

## Cerita Singkat Vuejs
Vue awalnya dibuat oleh Evan You pada tahun 2013.

Evan You sebelumnya bekerja di Google dengan Angularjs. Dia kemudian punya ide untuk membuat sesuatu yang lebih ringan dari Angular.

Dari sanalah ia mulai membuat Vuejs.

Versi pertama (0.6) dirilis pada tanggal 8 desember 2013, selanjutnya berlanjut ke versi 0.7 pada tanggal 24 desember 2013.

## Tools Bekerja Vuejs
Ada beberapa tools siapkan untuk bekerja dengan Vuejs:

1. Teks Editor
2. Nodejs dan NPM
3. Vue CLI
4. Web Browser

## Memahami Struktur Dasar kode Vuejs

Setiap kita akan menggunakan Vuejs, kita harus mengimpor atau menyisipkannya ke dalam kode HTML.

Pada contoh di atas, kita menggunakan Vuejs yang dari CDN dengan kode ini:

```<script src="https://cdn.jsdelivr.net/npm/vue"></script>```

Kemudian setelah itu, kita membutuhkan elemen kontainer yang akan digunakan oleh Vue untuk menampilkan data.

```<!-- elemen kontainer untuk aplikasi -->```
```
<div id="app">
    {{ data }}
</div>
```

Terakhir, kita harus membuat objek app dari class Vue() dan menentukan elemen serta data yang akan ditampilkan.
```
<script>
    var app = new Vue({
        el: "#app",
        data: {
            message: "Hello Codepolitan!"
        }
    })
</script>
```
Atribut el berfungsi untuk memilih elemen, pada contoh di atas kita akan memilih elemen dengan id="app". Lalu atribut data berfungsi untuk menyimpan variabel yang berisi data.