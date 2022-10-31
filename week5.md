## Web Server
Web server adalah sebuah perangkat lunak server yang menyediakan tempat untuk mendeploy sebuah website, seperti netfliy atau webhosting000. Untuk membuat server kita juga perlu terhubung ke internet. Untuk menghubungkan server maka kita memerlukan sebuah HTTP. Kemudian ada juga web service, yaitu tempat yang menyediakan layanan untuk berinteraksi antar aplikasi.

* ### Static Web Server dan Dynamic Web Server
    Server static adalah sebuah server berbentuk HTTP yang filenya hanya bisa berbentuk statis, seperti html, css dan js. Sedangkan Dynamic site adalah sebuah web yang memungkinan penggunanya mengubah langsung konten yang ada, seperti menambah, menghapus atau mengedit yang ada dalam database.

    Kemudian ada server side, yang merupakan server yang menunggu request dari klien, saat pesan diterima maka akan diberikan respons dengan HTTP. Respons yang diberikan merupakan hal yang diminta dari sisi klien, seperti halaman HTML, teks atau gambar.

    Contoh dari static web server.

    ![w1](https://user-images.githubusercontent.com/114371403/199023369-52e32d28-76c0-4c2f-b99f-7cd6e1d591ea.png)

    Contoh dari dynamic web server.

    ![w2](https://user-images.githubusercontent.com/114371403/199023387-3f879b56-df31-4d6a-bfa9-2ce11e7bbb21.png)

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

    ![w3](https://user-images.githubusercontent.com/114371403/199023395-c06bde31-0764-4d0c-b19f-79293f8197ee.png)

    Cara menjalankan programnya dengan mengetik "node" kemudian diikuti nama file js nya.

    ![w4](https://user-images.githubusercontent.com/114371403/199023403-7c385e5e-f462-4d04-b2c3-dfb2de85999b.png)

    Atau menggunakan fungsi lain seperti util untuk memasukkan data.

    ![w5](https://user-images.githubusercontent.com/114371403/199023407-6c04da97-49dd-4adb-8fe3-cbf0cd361916.png)

    Penggunaan %s untuk tipe data string dan %d untuk integer.

    ![w6](https://user-images.githubusercontent.com/114371403/199023412-9bb6e475-e42e-4492-a69b-3790cfcfe581.png)

    Kemudian kita juga bisa membuat file ".env", yang mana ini adalah file yang bersifat rahasia, yang menyimpan variabel penting atau link server.

    Contoh nya seperti dibawah ini, kita gunakan juga fungsi "fs" untuk membaca file nya.

    ![w7](https://user-images.githubusercontent.com/114371403/199023416-d825c87d-ba86-4273-a920-5e7e90e8219a.png)

    ![w8](https://user-images.githubusercontent.com/114371403/199023421-5aaec5db-f4c8-4716-948a-83c3e385878e.png)

    ![w9](https://user-images.githubusercontent.com/114371403/199023429-4982a94c-8edb-47dc-b780-5374fc98d40b.png)

* ### NPM
    Kita juga bisa dapat mengelola sebuah package secara otomatis, yaitu dengan menggunakan "npm". Pertama kita perlu melakukan inisialisasi pada terminal.

    ![w10](https://user-images.githubusercontent.com/114371403/199023434-3f67277b-f347-4212-ba2a-8f2fe325d515.png)

    Maka "package.json" akan dibuat oleh sistem. Kita bisa menjalankan program dengan memanggil npm. Kemudian nama filenya. Pastikan juga nama filenya sama ya dengan nama modulenya.

    ![w11](https://user-images.githubusercontent.com/114371403/199023440-41191eaf-b0d2-4806-ad9c-d7a1554c33f4.png)

    Kita buat module "events" nya di package.json.

    ![w12](https://user-images.githubusercontent.com/114371403/199023449-f45ce372-2a58-4779-81a1-2eda268c1050.png)

    Kemudian untuk manggilnya kita syntax "npm run" dan nama modulenya.

    ![w13](https://user-images.githubusercontent.com/114371403/199023452-21243b75-e9f6-41b2-a677-6c9cc951f0c7.png)

* ### Dotenv
    Saat kita memanggil sebuah module, terkadang file dari .env tidak dapat dipanggil.

    ![w14](https://user-images.githubusercontent.com/114371403/199023457-9c099bc8-b7b9-44a8-9683-d6800b7c02cd.png)

    ![w15](https://user-images.githubusercontent.com/114371403/199023462-7cbea0ae-a8ba-46fd-871a-496b3230006e.png)

    ![w16](https://user-images.githubusercontent.com/114371403/199023468-e52ceae2-2456-4e19-bda8-66dcd59ce555.png)

    Oleh karena itu kita dapat menggunkan module dotenv, yang akan menyimpan variabel dari env. Pertama kita perlu menginisialisasi dotenv.

    ![w17](https://user-images.githubusercontent.com/114371403/199023473-b7cb1702-7dae-46a1-a0f9-5f5280d2bc34.png)

    Maka package baru akan dibuat.

    ![w18](https://user-images.githubusercontent.com/114371403/199023477-56cc26cd-eaa8-4ed2-bfb2-622380a548d9.png)

    Nah sekarang kita panggil module dotenvnya, maka program akan berjalan. 

    ![w19](https://user-images.githubusercontent.com/114371403/199023484-4bf6cbd2-08c3-46f5-8e22-79889199e0ff.png)

    ![w20](https://user-images.githubusercontent.com/114371403/199023491-59e32733-066c-4fc0-a413-4ce2522a6a54.png)

* ### Membuat server
    Berdasarkan fungsi yang dijelaskan sebelumnya, node.js dapat melakukan berbagai fungsi, salah satunya adalah membuat server. Dalam node.js sudah terdapat module HTTP. module HTTP ini dapat melakukan request dan respons kepada klien.

    Contoh penerapannya adalah seperti dibawah ini. 

    ![w21](https://user-images.githubusercontent.com/114371403/199023494-313e372c-51b1-4cff-8200-5a7beb3affb5.png)

    Untuk membuat server kita perlu mamnggil fungsi .createServer, kemudian salah satu hal terpeting adalah memasukkan request dan respons di dalam parameternya. Penggunaan request atau disingkat res bertujuan untuk menangkap permintaan dari sisi klien, sedangkan respons atau disingkat res bertujuan untuk memberikan tanggapan kepada klien.
    
    Kemudian listen akan menangkap dan menghubungkan dengan port yang dituju, yang di tuju adalah port 8080. Dan untuk nomor port nya sendiri bisa kita sesuaikan ingin memakai yang mana. Maka saat di run dan kita panggil ke link port nya hasilnya adalah server yang kita buat.

    ![w22](https://user-images.githubusercontent.com/114371403/199023500-0ac4ba87-f1a7-4a97-9457-289e4f182d8c.png)

    ![w23](https://user-images.githubusercontent.com/114371403/199023503-badfddcd-2542-4cb8-b042-3bf706f190c7.png)

## Express
Express.js atau singkatnya Express, adalah salah satu framework yang berasal dari bahasa pemrograman JavaScript yang dirancang secara fleksibel dan minimalis untuk pengembangan aplikasi back-end. Framework hasil pengembangan dari Node.js ini bisa memberikan kemudahan dalam pembuatan aplikasi dari server-side.

Sebelum menggunakan express, pertama kita harus menginstall terlebih dahulu.

![w24](https://user-images.githubusercontent.com/114371403/199023507-5020911d-04f6-4cbf-a90c-919d61925868.png)

Untuk mempermudah development, kita bisa mengggunakan nodemon. Pertama perlu kita install terlebih dahulu.

![w25](https://user-images.githubusercontent.com/114371403/199023509-4ae04407-d0fe-461b-94fa-b305cedf1c68.png)

* ### Membuat server dengan Express
    Kemudian cara untuk menginisialisasinya cukup mirip dengan http. Bedanya kita dapat memberikan sebuah page atau folder didalam servernya.

    ![w26](https://user-images.githubusercontent.com/114371403/199023512-26387054-db79-4e01-a437-83de01a0c3c2.png)

    Maka hasilnya ketika kita run dan panggil servernya.

    ![w27](https://user-images.githubusercontent.com/114371403/199023517-ed145923-5440-4a0b-b02c-bbdb7245a417.png)

    Kita juga bisa membuat lebih dari 1 page atau folder dalam server yang sama.

    ![w28](https://user-images.githubusercontent.com/114371403/199023521-f6fa3a15-50ca-419d-b817-85130efff979.png)

    ![w29](https://user-images.githubusercontent.com/114371403/199023529-3c9a8d4a-55d4-4f69-8732-211bbc525fb4.png)

    Kita juga bisa menambah atau mengubah data yang ada dalam server, namun server nya akan minta di run ulang. Oleh karena itu kita gunakan nodemon agar server tetap bisa berjalan terus tanpa kita run ulang.

    Pertama kita perlu membuat fungsi nodemon di package.json.

    ![w30](https://user-images.githubusercontent.com/114371403/199023543-ece35453-616c-4803-b38f-c0c373cd10cd.png)

    Kemudian kita jalankan menggunakan npm, yang dipanggil adalah nama fungsi nya yang ada di package.json.

    ![w31](https://user-images.githubusercontent.com/114371403/199023548-de66c532-7446-4b77-abfc-cfaadce0bc06.png)

    Maka server yang kita buat akan terus berjalan.

* ### Middleware
    Middleware adalah sebuah fungsi yang dapat mengakses request dan response. Middleware merupakan penengah, kalau di dalam aplikasi middleware adalah sebuah aturan yang harus dilewati oleh sistem terlebih dahulu untuk masuk atau keluar dari sistem.

    Contoh nya kita memberikan pesan saat mengirim ke server, maka kita buat sebuah fungsi middleware.

    ![w32](https://user-images.githubusercontent.com/114371403/199023556-0e9dfb35-85e9-4b8d-a3ae-667c93f05231.png)

    Kita gunakan dengan fungsi .use untuk menggunakan middlewarenya. Dan ketika dijalankan maka pesan yang dilwati dari middlware akan ditampilkan di terminal.

    ![w33](https://user-images.githubusercontent.com/114371403/199023561-60b99fe9-faf3-4214-b666-71a16ee8b37d.png)

    Contoh penggunaan lainnya adalah kita dapat menghentikan request dan respone.

    ![w34](https://user-images.githubusercontent.com/114371403/199023562-7c8bb1fb-88da-40d8-955e-7b2e2774edc7.png)

    Maka outputnya tidak hanya di terminal, tetapi juga di tampilan web servernya.

    ![w35](https://user-images.githubusercontent.com/114371403/199023568-68b39f5e-4a60-4344-9e83-d2996c891ada.png)

    ![w36](https://user-images.githubusercontent.com/114371403/199023573-1b92baf2-28aa-4fdc-bea1-85d0fcc0710a.png)

* ### Routes
    Routes merupakan sebuah penghubung antara request dan response. Ketika user mengirimkan request pada aplikasi melalui sebuah URL, maka server akan menampung request dan akan memutuskan untuk mengeksekusi response mana yang akan dijalankan.

    Contoh, disini kita buat lebih dari 1 file, posisi nya juga kita tempatkan di folder yang berbeda.

    ![w37](https://user-images.githubusercontent.com/114371403/199023578-0f2e9bb1-bef3-4953-9b47-ba5da41d2dde.png)
    
    Untuk PORT menghubungkan ke servernya kita taroh di file rezieq.js, disini juga akan kita run dengan fungsi dari nodemon. Untuk menghubungkan nya dengan file lain kita gunakan router, kemudian file atau folder yang dituju.

    ![w38](https://user-images.githubusercontent.com/114371403/199023582-6a945e92-c3ab-4e43-bfed-73228d050da4.png)

    Setelah itu di file yang dituju yaitu index.js dan daftar.js, maka selanjutnya kita buat halaman servernya. Masing-masing dapat dibuat file yang berbeda.

    ![w39](https://user-images.githubusercontent.com/114371403/199023584-a96e97f0-194d-4fb8-a37d-ecd7f0430548.png)

    kemudian agar fungsi atau variabel dapat diakses diluar file, maka kita gunakan "module.exports".

    ![w40](https://user-images.githubusercontent.com/114371403/199023590-03ad2741-1f66-46a1-be12-48bafb229c0d.png)

    Ketika dijalankan dan di akses servernya maka akan ditampilkan sesuai page dari server yang ada di filenya. Dibawah ini page dari file index.js. dengan endpoint nya tidak ada.

    ![w41](https://user-images.githubusercontent.com/114371403/199023596-afd60aea-9b01-4c37-9e83-2fdab32cca1e.png)

    Dan ini page dari file daftar.js dengan endpoint daftar.

    ![w42](https://user-images.githubusercontent.com/114371403/199023599-e55deb9a-d0f9-4352-b4f0-401283e35918.png)

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

    ![w43](https://user-images.githubusercontent.com/114371403/199023603-d005428a-7b0a-4354-bb06-bfb3e86958cd.png)

    Dari ERD di atas terdapat 4 entitas, yaitu perawat, pasien, kasur dan ruangan. Setiap entitas juga memiliki atributnya masing-masing, misal entitas pasien memiliki atribut no_pasien sebagai primary key dan nama_pasien, kemudian entitas kasur memiliki atribut no_kasur sebagai primary key dan no_pasien sebagai foreign key dari entitas pasien.

    Tiap entitas juga memiliki relasi dan kardinalitasnya masing-masing. Misal, relasi antar pasien dan kasur, yang mana setiap pasien hanya bisa tidur di satu kasur dan begitu juga sebaliknya, satu kasur hanya bisa ditempati satu pasien. Biasa disebut juga relasi one to one.

    Kemudian relasi antar pasien dan ruangan, yang mana banyak pasien ditempati dalam satu ruangan, dan satu ruangan ditempati banyak pasien. Biasa disebut relasi one to many.

    Terakhir relasi antar pasien dan perawat, yang mana banyak pasien dirawat oleh banyak perawat dan begitu juga sebaliknya, banyak perawat merawat banyak pasien. Biasa disebut juga relasi many to many, dan dalam relasi many to many kita harus membuat entitas baru yang menyimpan atribut foreign key dari kedua entitas yang berlasi.

* ### Normalisasi
    Normalisasi merupakan sebuah teknik logical desain dalam sebuah mendesain database yang mengelompokkan atribut dari berbagai entitas dalam suatu relasi sehingga membentuk struktur relasi yang baik (tanpa redudansi/pengulangan data) serta sebagian besar ambigu dapat dihilangkan.

    Ada tahapan dalam melakukan normalisasi, yaitu dari 1NF, 2NF hingga seterusnya.

    Untuk melakukan normalisasi database kita harus mengidentifikasi data seperti apa yang akan disimpan.

    Contoh, kita memiliki sebuah data seperti dibawah ini.

    ![w44](https://user-images.githubusercontent.com/114371403/199023614-302ad91b-8709-4665-9c53-1f4229deafed.png)

    Pertama-tama kita lakukan normalisasi 1NF, yaitu harus menggunakan tipe data yang sama dalam satu kolom, harus ada primary key dan tiap kolom harus berisi nilai tunggal.

    Dari data di atas dari kolom film memiliki 2 nilai, jadi harus kita pecah.

    ![w45](https://user-images.githubusercontent.com/114371403/199023617-7bd67a2a-b095-4a3b-bd98-8438b0a9a441.png)

    Setelah melakukan bentuk 1NF, kita lanjutkan ke bentuk 2NF. Di 2NF tabel harus dipecah berdasarkan primary key nya atau jika tidak ada hubungan dengan primary key nya maka dipisah.

    ![w46](https://user-images.githubusercontent.com/114371403/199023623-e79fa69a-fb9b-4236-8218-9b4c5db17e36.png)

    ![w47](https://user-images.githubusercontent.com/114371403/199023630-d1bcc713-f9f1-41c2-af64-26cecc920fe8.png)

    Kemudian kita bisa melakukan bentuk 3 NF. Jika terdapat suatu atribut yang tidak bergantung pada primary key tapi bergantung pada field yang lain maka atribut-atribut tersebut perlu dipisah ke tabel baru. Jadi di sini makin banyak kita buat entitas baru.

    ![w48](https://user-images.githubusercontent.com/114371403/199023638-7e3ff329-6856-4aa3-8a6c-841b48a3feb6.png)

    ![w49](https://user-images.githubusercontent.com/114371403/199023643-206bfceb-06f4-4562-ab60-2a6dc86e80be.png)

    ![w50](https://user-images.githubusercontent.com/114371403/199023647-265634c8-1989-4a95-8bd3-14396c3a40ae.png)

    ![w51](https://user-images.githubusercontent.com/114371403/199023655-d7807032-f946-4e99-8c16-eb6ef064f422.png)
