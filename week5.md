## Web Server
Web server adalah sebuah perangkat lunak server yang menyediakan tempat untuk mendeploy sebuah website, seperti netfliy atau webhosting000. Untuk membuat server kita juga perlu terhubung ke internet. Untuk menghubungkan server maka kita memerlukan sebuah HTTP. Kemudian ada juga web service, yaitu tempat yang menyediakan layanan untuk berinteraksi antar aplikasi.

* ### Static Web Server dan Dynamic Web Server
    Server static adalah sebuah server berbentuk HTTP yang filenya hanya bisa berbentuk statis, seperti html, css dan js. Sedangkan Dynamic site adalah sebuah web yang memungkinan penggunanya mengubah langsung konten yang ada, seperti menambah, menghapus atau mengedit yang ada dalam database.

    Kemudian ada server side, yang merupakan server yang menunggu request dari klien, saat pesan diterima maka akan diberikan respons dengan HTTP. Respons yang diberikan merupakan hal yang diminta dari sisi klien, seperti halaman HTML, teks atau gambar.

    Contoh dari static web server.

    ![w1](w1.png)

    Contoh dari dynamic web server.

    ![w2](w2.png)

* ### Perbedaan Database dan Server
    Server adalah perangkat keras atau program komputer yang dapat digunakan secara bersamaan untuk memberikan layanannya ke beberapa klien, yaitu host atau pengguna. Di sisi lain, database digunakan untuk mengatur dan menyimpan informasi atau data yang dihasilkan oleh program komputer atau mesin itu sendiri.

## RESTful API
REST adalah sebuah arsitektur yang menyediakan sistem antar komputer di web untuk memudahkan komunikasi. Cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada data/resource pada REST server dimana masing-masing resource atau data/resource tersebut akan dibedakan oleh sebuah global ID atau URL.

Kemudian untuk metode HTTP dalam REST API antara lain :

- GET, berfungsi untuk membaca data
- POST, berfungsi untuk membuat sebuah data baru
- PUT, berfungsi untuk memperbaharui data
- DELETE, berfungsi untuk menghapus data

## Node.js
Node.js merupakan sebuah bahasa pemrograman javascript yang dapat diakses dimana saja, tidak terpatok hanya pada web. Jadi saat kita menggunakan node.js kita tidak bisa menggunakan DOM. Salah satu penggunannya adalah dapat digunakan untuk membuat aplikasi jaringan server.

Main fitur yang ada dalam node.js adalah :

- File System
- Http dan Https
- REPL (Read, Eval, Print, Loop)
- Console

* ### Menggunakan node.js
    Di dalam penggunaan node.js ada banyak fungsi yang bisa digunakan, seperti melihat versi OS yang kita pakai.

    ![w3](w3.png)

    Cara menjalankan programnya dengan mengetik "node" kemudian diikuti nama file js nya.

    ![w4](w4.png)

    Atau menggunakan fungsi lain seperti util untuk memasukkan data.

    ![w5](w5.png)

    Penggunaan %s untuk tipe data string dan %d untuk integer.

    ![w6](w6.png)

    Kemudian kita juga bisa membuat file ".env", yang mana ini adalah file yang bersifat rahasia, yang menyimpan variabel penting atau link server.

    Contoh nya seperti dibawah ini, kita gunakan juga fungsi "fs" untuk membaca file nya.

    ![w7](w7.png)

    ![w8](w8.png)

    ![w9](w9.png)

* ### NPM
    Kita juga bisa dapat mengelola sebuah package secara otomatis, yaitu dengan menggunakan "npm". Pertama kita perlu melakukan inisialisasi pada terminal.

    ![w10](w10.png)

    Maka "package.json" akan dibuat oleh sistem. Kita bisa menjalankan program dengan memanggil npm. Kemudian nama filenya. Pastikan juga nama filenya sama ya dengan nama modulenya.

    ![w11](w11.png)

    Kita buat module "events" nya di package.json.

    ![w12](w12.png)

    Kemudian untuk manggilnya kita syntax "npm run" dan nama modulenya.

    ![w13](w13.png)

* ### Dotenv
    Saat kita memanggil sebuah module, terkadang file dari .env tidak dapat dipanggil.

    ![w14](w14.png)

    ![w15](w15.png)

    ![w16](w16.png)

    Oleh karena itu kita dapat menggunkan module dotenv, yang akan menyimpan variabel dari env. Pertama kita perlu menginisialisasi dotenv.

    ![w17](w17.png)

    Maka package baru akan dibuat.

    ![w18](w18.png)

    Nah sekarang kita panggil module dotenvnya, maka program akan berjalan. 

    ![w19](w19.png)

    ![w20](w20.png)

* ### Membuat server
    Berdasarkan fungsi yang dijelaskan sebelumnya, node.js dapat melakukan berbagai fungsi, salah satunya adalah membuat server. Dalam node.js sudah terdapat module HTTP. module HTTP ini dapat melakukan request dan respons kepada klien.

    Contoh penerapannya adalah seperti dibawah ini. 

    ![w21](w21.png)

    Untuk membuat server kita perlu mamnggil fungsi .createServer, kemudian salah satu hal terpeting adalah memasukkan request dan respons di dalam parameternya. Penggunaan request atau disingkat res bertujuan untuk menangkap permintaan dari sisi klien, sedangkan respons atau disingkat res bertujuan untuk memberikan tanggapan kepada klien.
    
    Kemudian listen akan menangkap dan menghubungkan dengan port yang dituju, yang di tuju adalah port 8080. Dan untuk nomor port nya sendiri bisa kita sesuaikan ingin memakai yang mana. Maka saat di run dan kita panggil ke link port nya hasilnya adalah server yang kita buat.

    ![w22](w22.png)

    ![w23](w23.png)

## Express
Express.js atau singkatnya Express, adalah salah satu framework yang berasal dari bahasa pemrograman JavaScript yang dirancang secara fleksibel dan minimalis untuk pengembangan aplikasi back-end. Framework hasil pengembangan dari Node.js ini bisa memberikan kemudahan dalam pembuatan aplikasi dari server-side.

Sebelum menggunakan express, pertama kita harus menginstall terlebih dahulu.

![w24](w24.png)

Untuk mempermudah development, kita bisa mengggunakan nodemon. Pertama perlu kita install terlebih dahulu.

![w25](w25.png)

* ### Membuat server dengan Express
    Kemudian cara untuk menginisialisasinya cukup mirip dengan http. Bedanya kita dapat memberikan sebuah page atau folder didalam servernya.

    ![w26](w26.png)

    Maka hasilnya ketika kita run dan panggil servernya.

    ![w27](w27.png)

    Kita juga bisa membuat lebih dari 1 page atau folder dalam server yang sama.

    ![w28](w28.png)

    ![w29](w29.png)

    Kita juga bisa menambah atau mengubah data yang ada dalam server, namun server nya akan minta di run ulang. Oleh karena itu kita gunakan nodemon agar server tetap bisa berjalan terus tanpa kita run ulang.

    Pertama kita perlu membuat fungsi nodemon di package.json.

    ![w30](w30.png)

    Kemudian kita jalankan menggunakan npm, yang dipanggil adalah nama fungsi nya yang ada di package.json.

    ![w31](w31.png)

    Maka server yang kita buat akan terus berjalan.

* ### Middleware
    Middleware adalah sebuah fungsi yang dapat mengakses request dan response. Middleware merupakan penengah, kalau di dalam aplikasi middleware adalah sebuah aturan yang harus dilewati oleh sistem terlebih dahulu untuk masuk atau keluar dari sistem.

    Contoh nya kita memberikan pesan saat mengirim ke server, maka kita buat sebuah fungsi middleware.

    ![w32](w32.png)

    Kita gunakan dengan fungsi .use untuk menggunakan middlewarenya. Dan ketika dijalankan maka pesan yang dilwati dari middlware akan ditampilkan di terminal.

    ![w33](w33.png)

    Contoh penggunaan lainnya adalah kita dapat menghentikan request dan respone.

    ![w34](w34.png)

    Maka outputnya tidak hanya di terminal, tetapi juga di tampilan web servernya.

    ![w35](w35.png)

    ![w36](w36.png)

* ### Routes
    Routes merupakan sebuah penghubung antara request dan response. Ketika user mengirimkan request pada aplikasi melalui sebuah URL, maka server akan menampung request dan akan memutuskan untuk mengeksekusi response mana yang akan dijalankan.

    Contoh, disini kita buat lebih dari 1 file, posisi nya juga kita tempatkan di folder yang berbeda.

    ![w37](w37.png)
    
    Untuk PORT menghubungkan ke servernya kita taroh di file rezieq.js, disini juga akan kita run dengan fungsi dari nodemon. Untuk menghubungkan nya dengan file lain kita gunakan router, kemudian file atau folder yang dituju.

    ![w38](w38.png)

    Setelah itu di file yang dituju yaitu index.js dan daftar.js, maka selanjutnya kita buat halaman servernya. Masing-masing dapat dibuat file yang berbeda.

    ![w39](w39.png)

    kemudian agar fungsi atau variabel dapat diakses diluar file, maka kita gunakan "module.exports".

    ![w40](w40.png)

    Ketika dijalankan dan di akses servernya maka akan ditampilkan sesuai page dari server yang ada di filenya. Dibawah ini page dari file index.js. dengan endpoint nya tidak ada.

    ![w41](w41.png)

    Dan ini page dari file daftar.js dengan endpoint daftar.

    ![w42](w42.png)

## Design Database
Dalam membuat sebuah program yang mampu menampung data, maka dibutuhkan sebuah database. Namun sebelum membuat program databasenya, kita perlu membuat rancangan database yang akan kita buat. Biasa dikenal juga dengan Entity Relationship Diagram.

* ### Entity Relationship Diagram (ERD)
    Komponen yang ada dalam ERD antara lain entitas, atribut dan relasi.

    - Entitas
    Entitas adalah sebuah tempat yang menyimpan atribut. Biasa digambarkan dengan persegi panjang.

    - Atribut
    Atribut adalah isi yang ada dari entitas, yang mana menggambarkan objek dari entitas tersebut. Biasa digambarkan dengan lingkaran.

    - Relasi
    Relasi adalah hubungan antar entitas, yang mana relasi ini memiliki kardinalitas yang mempengaruhi fungsi antar entitas. Biasa digambarkan dengan belah ketupat.

    - Primary Key
    Primary key merupakan kode unik atribut dari setiap entitas. Biasa digambarkan dengan tanda pagar atau bintang.

    - Foreign Key
    Foreign key adalah atribut yang terhubung dengan entitas lain. Biasa digambarkan dengan huruf depan f atau garis bawah.

    Contoh ERD dibawah ini adalah rumah sakit.

    ![w43](w43.png)

    Dari ERD di atas terdapat 4 entitas, yaitu perawat, pasien, kasur dan ruangan. Setiap entitas juga memiliki atributnya masing-masing, misal entitas pasien memiliki atribut no_pasien sebagai primary key dan nama_pasien, kemudian entitas kasur memiliki atribut no_kasur sebagai primary key dan no_pasien sebagai foreign key dari entitas pasien.

    Tiap entitas juga memiliki relasi dan kardinalitasnya masing-masing. Misal, relasi antar pasien dan kasur, yang mana setiap pasien hanya bisa tidur di satu kasur dan begitu juga sebaliknya, satu kasur hanya bisa ditempati satu pasien. Biasa disebut juga relasi one to one.

    Kemudian relasi antar pasien dan ruangan, yang mana banyak pasien ditempati dalam satu ruangan, dan satu ruangan ditempati banyak pasien. Biasa disebut relasi one to many.

    Terakhir relasi antar pasien dan perawat, yang mana banyak pasien dirawat oleh banyak perawat dan begitu juga sebaliknya, banyak perawat merawat banyak pasien. Biasa disebut juga relasi many to many, dan dalam relasi many to many kita harus membuat entitas baru yang menyimpan atribut foreign key dari kedua entitas yang berlasi.

* ### Normalisasi
    Normalisasi merupakan sebuah teknik logical desain dalam sebuah mendesain database yang mengelompokkan atribut dari berbagai entitas dalam suatu relasi sehingga membentuk struktur relasi yang baik (tanpa redudansi/pengulangan data) serta sebagian besar ambigu dapat dihilangkan.

    Ada tahapan dalam melakukan normalisasi, yaitu dari 1NF, 2NF hingga seterusnya.

    Untuk melakukan normalisasi database kita harus mengidentifikasi data seperti apa yang akan disimpan.

    Contoh, kita memiliki sebuah data seperti dibawah ini.

    ![w44](w44.png)

    Pertama-tama kita lakukan normalisasi 1NF, yaitu harus menggunakan tipe data yang sama dalam satu kolom, harus ada primary key dan tiap kolom harus berisi nilai tunggal.

    Dari data di atas dari kolom film memiliki 2 nilai, jadi harus kita pecah.

    ![w45](w45.png)

    Setelah melakukan bentuk 1NF, kita lanjutkan ke bentuk 2NF. Di 2NF tabel harus dipecah berdasarkan primary key nya atau jika tidak ada hubungan dengan primary key nya maka dipisah.

    ![w46](w46.png)

    ![w47](w47.png)

    Kemudian kita bisa melakukan bentuk 3 NF. Jika terdapat suatu atribut yang tidak bergantung pada primary key tapi bergantung pada field yang lain maka atribut-atribut tersebut perlu dipisah ke tabel baru. Jadi di sini makin banyak kita buat entitas baru.

    ![w48](w48.png)

    ![w48](w48.png)

    ![w49](w49.png)

    ![w50](w50.png)

    ![w51](w51.png)