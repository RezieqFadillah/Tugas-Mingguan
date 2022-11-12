## Sequelize
* ### Menangambil data dari Database
    Setelah kita membuat berhasil membuat database, sekarang kita dapat memanggilnya. Caranya adalah dengan kita membuat fungsi di endpoint nya. Namun sebelum membuat fungsinya, kita perlu tau terlebih dahulu posisi endpointnya dari file mana.

    Pertama dari file routes/index.js, terdapat endpoint /user, nah ini kita exports agar bisa digunakan diluar file.

    ![w1](https://user-images.githubusercontent.com/114371403/201452170-5ce2d355-f40d-49f7-a45f-afdac5b54638.png)

    kemudian di file routes/user.router.js terdapat berbagai endpoint yang kita buat berdasarkan fungsinya.

    ![w2](https://user-images.githubusercontent.com/114371403/201452174-d759e0b4-469c-4d12-8c84-ea690ecfdf6d.png)

    Di atas sudah kita ketahui posisi file fungsinya kita buat di file controllers/user.controller.js. Setelah kita mengetahui posisi endpoint nya, maka saat nya kita membuat fungsinya.

    Disini kita mau menampilkan seluruh data dari tabel users, pertama kita panggil dulu model yang telah kita definisikan di folder models, yaitu "User". 

    Ini file dari models/user.js

    ![w3](https://user-images.githubusercontent.com/114371403/201452176-68ebe005-751b-4900-9b5d-918de22663b6.png)

    Kemudian ini dari file controller yang terdapat endpointnya. Disini kita panggil dulu model yang telah kita destructor dengan mengambil data "User", kemudian kita buat fungsi nya. Kita buat variabel "user" untuk mengambil datanya, gunakan fungsi "findAll" untuk mengambil seluruh datanya. Kemudian kita berikan response dengan menampilkan datanya dengan memanggil variable "users".

    ![w4](https://user-images.githubusercontent.com/114371403/201452177-3bd20985-8f51-4464-812b-97ae1363d431.png)

    Maka ketika kita jalankan servernya, dia akan menampilkan database yang kita panggil tadi.

    ![w5](https://user-images.githubusercontent.com/114371403/201452179-b1b037df-5cba-4857-914d-0ff90e359e64.png)

    ![w6](https://user-images.githubusercontent.com/114371403/201452181-dc8e3809-5541-4588-a1e8-7c060423b0b9.png)

    Kita juga bisa membuat fungsi lain, seperti mengambil data berdasarkan id nya. Disini kita ambil objek id nya dengan request, kemudian kita samakan dengan parameter (params) di endpointnya. Selanjutnya kita gunakan fungsi "findByPk".

    ![w7](https://user-images.githubusercontent.com/114371403/201452184-b8f78e41-c8ce-4ba8-b911-9fc301207788.png)

    ![w8](https://user-images.githubusercontent.com/114371403/201452185-8852b044-8517-4edf-92d5-e931c51f4b80.png)

## MongoDB
MongoDB adalah sebuah database berbentuk noSQL. MongoDB dapat digunakan untuk menyimpan database seperti pada umumnya. Salah keunikan database berbentuk noSQL ia dapat menyimpan data dengan bebas, tanpa terpaku kolom atau field yang ada.

Untuk menggunakan MongoDB dengan mudah kita dapat menggunakan GUI dari MongoDB, yaitu compass.

* ### Menggunakan MongoDBcompass
    Pertama-tama kita perlu membuat koneksi.

    ![w9](https://user-images.githubusercontent.com/114371403/201452187-60738b04-dbcb-4571-8f70-adacdee3f413.png)

    Jika sudah maka kita akan masuk dan melihat database yang tersedia.

    ![w10](https://user-images.githubusercontent.com/114371403/201452188-9d825f78-9d96-4e29-9750-e387aaddb450.png)

    - Membuat database dan collection
        Untuk membuat database kita bisa mengklik "create database". Dalam mongo terdapat collection, collection ini dalam sql sama dengan table.

        ![w11](https://user-images.githubusercontent.com/114371403/201452190-77e05f2c-c275-4e13-8fd5-d8386ce236d0.png)

        Maka database akan dibuat.

        ![w12](https://user-images.githubusercontent.com/114371403/201452191-2f337e75-1ac6-4c07-9e57-43c33ffc9633.png)

        ![w13](https://user-images.githubusercontent.com/114371403/201452192-de2f8450-d2a8-4d5a-8605-9d1fbaf76a26.png)

    - Menginputkan data ke collection
        Kemudian untuk mengisi data ke collection kita bisa dengan menginputkan data.

        ![w14](https://user-images.githubusercontent.com/114371403/201452199-d1575fca-eaab-4c7a-bdc2-98df319ba9e8.png)

        Isi data nya dan insert.

        ![w15](https://user-images.githubusercontent.com/114371403/201452202-fec216ea-f8d5-4745-bff2-517af6b787f6.png)

        Maka datanya berhasil ditambahkan.

        ![w16](https://user-images.githubusercontent.com/114371403/201452205-e149db27-5c34-4a6b-8946-f6dcd2bd79bd.png)

* ### Membuat project dengan MongoDB
    Kita bisa menggunakan MongoDB sebagai database dari project dengan server yang kita buat. Pastikan kita telah mengistall mongodb dan mongoose terlebih dahulu.

    ![w17](https://user-images.githubusercontent.com/114371403/201452208-1e4e4054-6a72-4f51-b28f-652175c04479.png)

    ![w18](https://user-images.githubusercontent.com/114371403/201452210-fb8ed169-861b-490d-8b91-86aa9b57504c.png)

    Pertama-tama kita perlu membuat koneksi dengan database.

    ![w19](https://user-images.githubusercontent.com/114371403/201452211-2b01d3ef-f85a-471a-afd9-715accc0d8d5.png)

    ![w20](https://user-images.githubusercontent.com/114371403/201452213-9bc41d17-ed64-4095-9dad-1b6d87d7c3a6.png)

    Kita run, jika berhasil maka programnya akan berjalan.

    ![w21](https://user-images.githubusercontent.com/114371403/201452214-af4e914f-cef9-4987-81f2-69d970cc5bc3.png)

    Setelah itu kita buat file di models/user.js, kita mau membuat schema atau semacam tabel dengan atributnya di sql. Untuk membuat schema kita membutuhkan mongoose.

    ![w22](https://user-images.githubusercontent.com/114371403/201452215-2c4dd91f-ca0b-4175-845f-479158e340cf.png)

    Kemudian di file controllers/user.controller.js kita panggil database sesuai dengan endpoint servernya. Caranya juga mirip dengan sequelize.

    ![w23](https://user-images.githubusercontent.com/114371403/201452216-17cd2651-4b15-47c2-9df3-7602560f138b.png)

    Maka jika kita jalanakn servernya ia akan mengambil data dari database.

    ![w24](https://user-images.githubusercontent.com/114371403/201452218-37dad471-b32d-44df-8d65-d63f660b10e1.png)

    Kita juga bisa menambahkan data, cara nya kita perlu request untuk mengambil body data dari body. Kemudian buat objek untuk menyimpan datanya, dan simpan ke database.

    ![w25](https://user-images.githubusercontent.com/114371403/201452219-9bcf41f0-9737-4513-8e14-3c6faf5351d2.png)

    Kita panggil servernya dan kita inputkan data baru, status nya berhasil.

    ![w26](https://user-images.githubusercontent.com/114371403/201452221-aeb6079f-aa37-4366-b54b-667894a226e6.png)

    Dan ini kita tampilkan datanya yang telah diinput tadi.

    ![w27](https://user-images.githubusercontent.com/114371403/201452222-72cdd099-17c3-481f-a53a-1230bd3000c9.png)

* ### Encryption
    Saat kita menginputkan password, data tersebut masuk ke sistem dengan tetap bentuk aslinya. Padahal password harus disamarkan agar tidak diketahui orang lain. Oleh karena itu kita gunakan enkripsi, dan enkripsi yang kita gunakan berbentuk hash.

    Pertama kita perlu menginstal bcrypt untuk mengenkripsi datanya.

    ![w28](https://user-images.githubusercontent.com/114371403/201452223-0f0f64e4-eb66-43aa-81e6-86c7b3d01076.png)

    Jangan lupa juga kita panggil bcrypt nya.

    ![w29](https://user-images.githubusercontent.com/114371403/201452224-907ce888-03cd-45f6-9f39-cdc89aebdda4.png)

    Kemudian di endpoint menambahkan data kita buat fungsi, dari mengambil data dari bodynya. Kemudian kita buat "bumbu tambahan" untuk meningkatkan keamanan, yaitu "saltRounds" sebanyak 10. Kemudian kita buat variable baru (hash) untuk menampung fungsi yang menjalankan proses enkripsi, dimulai dari memanggil bcrypt nya dan metode enkripsi nya (hashSync), kemudian data yang ingin di enkripsi yaitu password, serta bumbu tambahan ikut dimasukkan.

    ![w30](https://user-images.githubusercontent.com/114371403/201452225-5324d14a-ca0b-4bc8-935c-c2a0c38a709a.png)

    Selanjutnya kita input datanya.

    ![w31](https://user-images.githubusercontent.com/114371403/201452226-01442f62-5718-4fc4-8737-f08e0f07ab25.png)

    Kita cek dan passwordnya akan dienkripsi.

    ![w32](https://user-images.githubusercontent.com/114371403/201452227-22e4b7f7-b10d-4f4d-b6ed-26db91d0f68e.png)

    ![w33](https://user-images.githubusercontent.com/114371403/201452228-a972164d-c30b-481e-99e7-7b6b3756e6fa.png)

* ### Reference
    Di mongodb kita bisa juga menggunakan foreign key seperti pada sql, nah dalam mongodb dikenal sebagai embed dan reference. Untuk menerapkan reference kita membutuhkan 2 collection yang berbeda, maka disini kita buat collection baru.

    Pertama kita buat dulu endpoint baru, yaitu tugas.

    ![w34](https://user-images.githubusercontent.com/114371403/201452230-b00e734a-00f1-4117-9862-a5a3e92a6b94.png)

    ![w35](https://user-images.githubusercontent.com/114371403/201452233-ac7d1e94-73c9-488e-967a-0292104d8dce.png)

    Kemudian kita buat schema baru untuk membuat atributnya. Di atribut "user" kita buat reference nya dengan menghungkan ObjectId nya dengan collection "User".

    ![w36](https://user-images.githubusercontent.com/114371403/201452234-c2d33745-db30-4ea5-be6b-44b5f446d5d5.png)

    Kemudian di controller nya kita buat fungsi seperti sebelumnya, yaitu untuk menginputkan data dari server.

    ![w37](https://user-images.githubusercontent.com/114371403/201452236-168a8193-f844-45bc-aefa-f20a2d47b993.png)

    Sekerang kita inputkan datanya, user yang menjadi reference harus menuju pada ObjectId yang ingin dituju.

    ![w38](https://user-images.githubusercontent.com/114371403/201452237-4827d027-3979-455e-8ffe-3043a5ef5ad0.png)

    ![w39](https://user-images.githubusercontent.com/114371403/201452239-0de74dcc-db6b-412c-9c13-d581ab0a63c0.png)

    Kemudian kita buat fungsi untuk mengambil datanya. Kita gunakan juga "populate untuk menampilkan atribut yang di inginkan, disini kita hanya ingin menampilkan atribut nama dari collection "User" yang menjadi ObjectId nya.

    ![w40](https://user-images.githubusercontent.com/114371403/201452247-d2ceb5df-4d59-4092-aec2-8310472fa369.png)

    Dan ini kita tampilkan datanya yang telah direference dengan collection "User".

    ![w41](https://user-images.githubusercontent.com/114371403/201452250-636ee31f-033c-43b4-b3a3-e277763b31bb.png)

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
