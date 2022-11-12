## Sequelize
* ### Menangambil data dari Database
    Setelah kita membuat berhasil membuat database, sekarang kita dapat memanggilnya. Caranya adalah dengan kita membuat fungsi di endpoint nya. Namun sebelum membuat fungsinya, kita perlu tau terlebih dahulu posisi endpointnya dari file mana.

    Pertama dari file routes/index.js, terdapat endpoint /user, nah ini kita exports agar bisa digunakan diluar file.

    ![w1](w1.png)

    kemudian di file routes/user.router.js terdapat berbagai endpoint yang kita buat berdasarkan fungsinya.

    ![w2](w2.png)

    Di atas sudah kita ketahui posisi file fungsinya kita buat di file controllers/user.controller.js. Setelah kita mengetahui posisi endpoint nya, maka saat nya kita membuat fungsinya.

    Disini kita mau menampilkan seluruh data dari tabel users, pertama kita panggil dulu model yang telah kita definisikan di folder models, yaitu "User". 

    Ini file dari models/user.js

    ![w3](w3.png)

    Kemudian ini dari file controller yang terdapat endpointnya. Disini kita panggil dulu model yang telah kita destructor dengan mengambil data "User", kemudian kita buat fungsi nya. Kita buat variabel "user" untuk mengambil datanya, gunakan fungsi "findAll" untuk mengambil seluruh datanya. Kemudian kita berikan response dengan menampilkan datanya dengan memanggil variable "users".

    ![w4](w4.png)

    Maka ketika kita jalankan servernya, dia akan menampilkan database yang kita panggil tadi.

    ![w5](w5.png)

    ![w6](w5.png)

    Kita juga bisa membuat fungsi lain, seperti mengambil data berdasarkan id nya. Disini kita ambil objek id nya dengan request, kemudian kita samakan dengan parameter (params) di endpointnya. Selanjutnya kita gunakan fungsi "findByPk".

    ![w7](w7.png)

    ![w8](w8.png)

## MongoDB
MongoDB adalah sebuah database berbentuk noSQL. MongoDB dapat digunakan untuk menyimpan database seperti pada umumnya. Salah keunikan database berbentuk noSQL ia dapat menyimpan data dengan bebas, tanpa terpaku kolom atau field yang ada.

Untuk menggunakan MongoDB dengan mudah kita dapat menggunakan GUI dari MongoDB, yaitu compass.

* ### Menggunakan MongoDBcompass
    Pertama-tama kita perlu membuat koneksi.

    ![w9](w9.png)

    Jika sudah maka kita akan masuk dan melihat database yang tersedia.

    ![w10](w10.png)

    - Membuat database dan collection
        Untuk membuat database kita bisa mengklik "create database". Dalam mongo terdapat collection, collection ini dalam sql sama dengan table.

        ![w11](w11.png)

        Maka database akan dibuat.

        ![w12](w12.png)

        ![w13](w13.png)

    - Menginputkan data ke collection
        Kemudian untuk mengisi data ke collection kita bisa dengan menginputkan data.

        ![w14](w14.png)

        Isi data nya dan insert.

        ![w15](w15.png)

        Maka datanya berhasil ditambahkan.

        ![w16](w16.png)

* ### Membuat project dengan MongoDB
    Kita bisa menggunakan MongoDB sebagai database dari project dengan server yang kita buat. Pastikan kita telah mengistall mongodb dan mongoose terlebih dahulu.

    ![w17](w17.png)

    ![w18](w18.png)

    Pertama-tama kita perlu membuat koneksi dengan database.

    ![w19](w19.png)

    ![w20](w20.png)

    Kita run, jika berhasil maka programnya akan berjalan.

    ![w21](w21.png)

    Setelah itu kita buat file di models/user.js, kita mau membuat schema atau semacam tabel dengan atributnya di sql. Untuk membuat schema kita membutuhkan mongoose.

    ![w22](w22.png)

    Kemudian di file controllers/user.controller.js kita panggil database sesuai dengan endpoint servernya. Caranya juga mirip dengan sequelize.

    ![w23](w23.png)

    Maka jika kita jalanakn servernya ia akan mengambil data dari database.

    ![w24](w24.png)

    Kita juga bisa menambahkan data, cara nya kita perlu request untuk mengambil body data dari body. Kemudian buat objek untuk menyimpan datanya, dan simpan ke database.

    ![w25](w25.png)

    Kita panggil servernya dan kita inputkan data baru, status nya berhasil.

    ![w26](w26.png)

    Dan ini kita tampilkan datanya yang telah diinput tadi.

    ![w27](w27.png)

* ### Encryption
    Saat kita menginputkan password, data tersebut masuk ke sistem dengan tetap bentuk aslinya. Padahal password harus disamarkan agar tidak diketahui orang lain. Oleh karena itu kita gunakan enkripsi, dan enkripsi yang kita gunakan berbentuk hash.

    Pertama kita perlu menginstal bcrypt untuk mengenkripsi datanya.

    ![w28](w28.png)

    Jangan lupa juga kita panggil bcrypt nya.

    ![w29](w29.png)

    Kemudian di endpoint menambahkan data kita buat fungsi, dari mengambil data dari bodynya. Kemudian kita buat "bumbu tambahan" untuk meningkatkan keamanan, yaitu "saltRounds" sebanyak 10. Kemudian kita buat variable baru (hash) untuk menampung fungsi yang menjalankan proses enkripsi, dimulai dari memanggil bcrypt nya dan metode enkripsi nya (hashSync), kemudian data yang ingin di enkripsi yaitu password, serta bumbu tambahan ikut dimasukkan.

    ![w30](w30.png)

    Selanjutnya kita input datanya.

    ![w31](w31.png)

    Kita cek dan passwordnya akan dienkripsi.

    ![w32](w32.png)

    ![w33](w33.png)

* ### Reference
    Di mongodb kita bisa juga menggunakan foreign key seperti pada sql, nah dalam mongodb dikenal sebagai embed dan reference. Untuk menerapkan reference kita membutuhkan 2 collection yang berbeda, maka disini kita buat collection baru.

    Pertama kita buat dulu endpoint baru, yaitu tugas.

    ![w34](w34.png)

    ![w35](w35.png)

    Kemudian kita buat schema baru untuk membuat atributnya. Di atribut "user" kita buat reference nya dengan menghungkan ObjectId nya dengan collection "User".

    ![w36](w36.png)

    Kemudian di controller nya kita buat fungsi seperti sebelumnya, yaitu untuk menginputkan data dari server.

    ![w37](w37.png)

    Sekerang kita inputkan datanya, user yang menjadi reference harus menuju pada ObjectId yang ingin dituju.

    ![w38](w38.png)

    ![w39](w39.png)

    Kemudian kita buat fungsi untuk mengambil datanya. Kita gunakan juga "populate untuk menampilkan atribut yang di inginkan, disini kita hanya ingin menampilkan atribut nama dari collection "User" yang menjadi ObjectId nya.

    ![w40](w40.png)

    Dan ini kita tampilkan datanya yang telah direference dengan collection "User".

    ![w41](w41.png)

## Docker
Docker adalah layanan yang menyediakan kemampuan untuk mengemas dan menjalankan sebuah aplikasi dalam sebuah lingkungan terisolasi yang disebut dengan container.

Dengan adanya isolasi dan keamanan yang memadai memungkinkan kita untuk menjalankan banyak container di waktu yang bersamaan pada host tertentu. Aplikasi yg berjalan di dalam container docker tidak terpengaruh oleh faktor luar karena terisolasi.

* ### Isi docker
    Terdapat beberapa isi dari docker yang dapat dijalankan, yaitu :
    - Docker File
        Blueprint untuk membuat image
    - Image
        Template untuk menjalankan container
    - Container
        Perwujudan Image
    - Docker Registry
        Tempat untuk upload atau download image
     
* ### Perintah Dasar
    - docker pull
        Untuk mendownload image dari hub
    - docker images
        Melihat kumpulan images yang sudah didownload
    - docker run
        Untuk menjalankan container
    - docker ps
        Untuk melihat container yang berjalan