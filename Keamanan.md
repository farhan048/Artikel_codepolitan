# Jenis - Jenis serangan Cyber Crime
Keamanan jaringan komputer sekarang adalah bagian yang penting dalam jaringan komputer. Solusi keamanan jaringan komputer terbentuk pada awal tahun 1960 tapi tidak terlalu pesat hingga awal tahun 2000. Keamanan jaringan diklasifikasi untuk mempermudah dalam mempelajarinya dan mengkategorikannya dengan benar. Virus, Worm, dan Trojan horse adalah contoh dari beberapa serangan yang ada. Tapi dalam pengelompokan umumnya ada 3 yaitu Reconnaissance, Access, atau Denial of Service (DoS).

langkah-langkah dasar melakukan serangan yaitu :

- **Reconnaisance**
  
adalah teknik paling awal sekali yang dilakukan oleh seorang hacker sebelum serangan dilakukan. Dengan cara ini seorang penyerang akan memperoleh informasi awal seperti, IP, DNS Server, Domain, Tabel Routing, reconnaisance dibagi menjadi 2 jenis, yaitu passive reconnaissance dan active reconnaissance. 
  - Passive reconnaissance adalah melakukan kegiatan reconnaissance tanpa berhubungan secara langsung dengan target, contoh : mendapatkan informasi melalui situs atau surat kabar. 
  - Active reconnaissance adalah melakukan kegiatan reconnaissance dengan cara berhubungan langsung dengan target, contoh : mendapatkan informasi melalui telepon atau email dengan target.
  
Intinya dari kegiatan ini adalah mendapatkan informasi detail sebanyak-banyaknya sebagai persiapan untuk melakukan langkah berikutnya. Pada proses ini ada beberapa langkah yang dilakukan, yaitu :

a.	Menentukan ruang lingkup aktifitas.

Pada proses ini kita akan mendapatkan sebanyak mungkin informasi yang berkaitan dengan lokasi, perusahaan, berita, alamat, email address, kebijakan, dll.

b.	Network Enumeration

dilakukan untuk melihat domain yang digunakan oleh sebuah organisasi. Dengan menggunakan tools “whois” kita dapat melakukan kegiatan ini.

c.	Mengetahui DNS record

Setelah kita mengetahui domain yang berkaitan dengan organisasi sasaran, selanjutnya kita perlu mencek hubungan alamat IP (IP address) & domain / hostname yang digunakan. Cara ini dapat dilakukan dengan menggunakan tools “See DNS Record” yang terdapat pada who.is.

d.	Mengintai Jaringan

Setelah mengetahui daftar alamat IP (IP address) dari berbagai host yang ada di target anda. Langkah selanjutnya adalah memetakan topologi jaringan, baik yang menuju ke target sasaran maupun konfigurasi internal jaringan target. Biasanya kita mengunakan software seperti traceroute (Linux / UNIX), tracert (Windows), atau menggunakan tools yang sudah di sediakan oleh who.is untuk melakukan pemetaan jaringan.
maka kita sudah mempunyai informasi dasar yang akan diperlukan untuk mendukung kegiatan selanjutnya.

- **Scanning**
  
merupakan kegiatan yang bertujuan untuk mencari celah jalur penyusupan yang lebih spesifik lagi. Ada 3 macam tipe dari scanning, yaitu port scanning, network scanning dan vulnerability scanning. Cara paling sederhana untuk melihat status suatu layanan pada server target diinternet adalah menggunakan software port scanner seperti NMAP. Dalam langkah ini hacker mendapatkan berbagai informasi-informasi yang dibutuhkan untuk melakukan penetrasi kedalam suatu sistem. Ada beberapa cara dalam melakukan kegiatan ini, yaitu menggunakan metode man in the middle attack, sniffing, atau brute force attack

- **Gaining Access**
  
dapat dikatakan fase penetrasi, dimana dalam fase ini hacker mengekploitasi kelemahan dari sistem yang sudah diketahui setelah melakukan kegiatan reconnaissance dan scanning. Hacker berusaha untuk mendapatkan hak akses. Pengeksploitasian kelemahan dari suatu sistem dapan dilakukan melalui LAN dan internet, contohnya adalah buffer overflow, denial of service, password cracking, session hijacking. Pada langkah ini maka hacker sudah memperoleh hak akses tingkat sistem operasi, aplikasi, dan jaringan.

- **Maintaning Access**

Pada tahap maintaining access, hacker mencoba untuk menahan hak akses kepemilikan suatu sistem yang diserang. Hacker juga dapat memperkuat sistem tersebut agar tidak dapat diserang oleh hacker lainnya, dan membuat akses ekslusif untuk mempertahankan hak akses dengan menggunakan Trojans, backdoors, atau rootkits sehingga hacker dapat masuk kembali ke sistem target dengan mudah. Hacker dapat memanipulasi, upload, download dan memanipulasi data dalam sistem tersebut.

- **Covering Track**
  
Tahap yang paling sulit untuk dilakukan dan merupakan fase yang sering dilupakan oleh hacker pada umumnya, ketika hacker meninggalkan jejak di log file (firewall, IDS, Sistem Operasi, dan aplikasi lainnya). Hacker pada umumnya lupa untuk membersihkan jejak. File-file log yang tertinggal di sistem yang mereka serang ini dapat di analisa dengan teknik-teknik forensik. Bahkan file log yang sudah dihapus oleh hacker dapat di retrieve sehingga bisa menjadi bukti ketika kasus tersebut akan dibawa ke insitusi terkait dengan kejahatan di dunia cyber.
 
- **Web : File upload vulnerability**
  
File Upload Vulnerabiliy adalah suatu celah keamanan pada sebuah website yang impact-nya sangat critical.  Celah keamanan ini berasal dari form upload file seperti dokumen, image atau lain sebagainya sesuai kebutuhan kita yang ada pada website, tujuan awal adanya fitur ini untuk mempermudah tetapi dapat salah digunakan oleh orang yang tidak bertanggungjawab dengan mengupload file yang tidak sesuai misal script program atau bahkan virus yang nantinya akan merusak sistem dari website kita.

Ada beberapa langkah untuk menghindari celah keamanan File Upload Vulnerability ini :
  - Hanya terima file yang ekstensi gambar atau dokumen yang diperlukan.
  - Cek tipe ekstensi dan mime file.
  - Jika mengunakan laravel bisa di validasi dahulu karena validasi bawaan laravel sudah cukup aman.
