## Database
Database adalah sebuah tempat yang menyimpan berbagai macam data. Kemudian sistem untuk menyimpan data ini teorganisir dan dapat dibuat bentuk nya sesuai dengan ERD (Entity Relationship). Bentuk dari database ini dari dibuat tersruktur, seperti memiliki tabel, kolom dan baris. Data yang ada dalam database sendiri bisa kita lakukan berbagai macam modifikasi, seperti menambah, mengurangi, mengubah dan menghapus data. 

## MySQL
Dalam membuat database kita membutuhkan sebuah sistem yang dapat meyimpan dan mengopersikan database, yaitu MySQL. MySQL ini dibuat agar dapat digunakan dengan mudah didalam website atau aplikasi apapun itu. 

* ### Perintah MySQL
    Dalam MySQL sub-perintah dibedakan menjadi 3, yaitu DDL, DML dan DCL, namun yang lebih sering digunakan adalah DDL dan DML.

    - DDL (Data Definition Language)
        DDL adalah cara kita dalam membuat struktur database, perintahnya seperti CREATE, ALTER, dan DROP. Contoh penerapannya seperti membuat database, membuat tabel, menambah kolom atau menghapus tabel.

        ![w1](https://user-images.githubusercontent.com/114371403/200436756-c9e4b8d5-833f-45dd-b190-d7bc48d55810.png)

        ![w2](https://user-images.githubusercontent.com/114371403/200436762-12c32b4a-4dd2-45d6-a1da-29a090ff977a.png)

        ![w3](https://user-images.githubusercontent.com/114371403/200436764-354ae320-786c-4706-9c71-ed8593359593.png)

    - DML (Data Manipulation Language)
        DML adalah cara untuk memanipulasi data yang ada di dalam tabel. Data yang dapat dimanipulasi seperti perintah yang dapat diberikan seperti SELECT, INSERT, UPDATE dan DELETE. Contoh penerapan seperti menambahkan data ke kolom, menampilkan data dan mengubah isi baris.

        ![w4](https://user-images.githubusercontent.com/114371403/200436767-4dcd776b-c0c4-450a-b8a1-d8858c7c7b47.png)

        ![w5](https://user-images.githubusercontent.com/114371403/200436769-b23e1a6b-882e-45ae-93fb-ff212f50c0f3.png)

        ![w6](https://user-images.githubusercontent.com/114371403/200436772-b3e2c425-13bf-4552-afb3-2e07d4009e0f.png)

* ### Menampilkan Data
    Ada perintah lain untuk menampilkan data, antara lain :
    - SHOW
        Bisa digunakan untuk menampilkan database ataupun seperti tabel.

        ![w7](https://user-images.githubusercontent.com/114371403/200436775-d7260f2c-42db-4a29-87ce-23a6c4f1c024.png)

        ![w8](https://user-images.githubusercontent.com/114371403/200436776-51613ede-92c0-4849-9f99-52ac33aa46a1.png)

    - DESC
        Digunakan untuk menampilkan struktur dari tabel.

        ![w9](https://user-images.githubusercontent.com/114371403/200436779-8c3611fb-49c1-474d-98f6-1833b6fc70a4.png)

        ![w10](https://user-images.githubusercontent.com/114371403/200436780-69bde769-7d6c-4289-9ca8-9f41f954df7b.png)

    - SELECT
        Digunakan untuk menampilkan nilai yang ada dalam baris. Cara penggunaanya adalah memanggil nama kolom yang ingin ditampilkan.

        ![w11](https://user-images.githubusercontent.com/114371403/200436785-4d347079-8fc7-4515-9fd3-65e4d27b707c.png)

        ![w12](https://user-images.githubusercontent.com/114371403/200436787-dc58227d-a5f3-431d-9445-fc78b1b55b05.png)

        Untuk menampikan seluruh data yang ada dalam kolom maka kita gunakan *.

        ![w13](https://user-images.githubusercontent.com/114371403/200436790-c7259fbe-c65a-4178-8a24-7484ef20f021.png)

        ![w14](https://user-images.githubusercontent.com/114371403/200436792-5afef2e8-ba03-4128-91ec-91d53a2703b7.png)

* ### Tipe Data dalam MySQL
    Di MySQL data yang akan disimpan disesuaikan dengan tipe data yang ada. Tipe data ini dibuat agar memudahkan kita dalam mengatur masing-masing tiap jenis data agar mudah dalam mengalokasikan datanya. Nah tipe data yang ada dalam SQL antara lain :

    - Number
        Number berisi kumpulan dengan karakter angka. Jenis-jenisnya antara lain INT dan FLOAT.

        ![w15](https://user-images.githubusercontent.com/114371403/200436794-0c93c296-5c39-4fee-b1c5-850e7c05a42b.png)

        ![w16](https://user-images.githubusercontent.com/114371403/200436799-93da8b73-a246-4be2-8488-3968a93ef0eb.png)

    - String
        String berisi kumpulan dengan karakter huruf, angka hingga simbol. Jenis-jenisnya antara lain CHAR, VARCHAR, TEXT dan ENUM.

        ![w17](https://user-images.githubusercontent.com/114371403/200436800-32ad580c-7381-43f4-a7e3-e1610829ff85.png)

    - DATE
        Data adalah tipe data yang untuk tanggal. Jenis-jenisnya antara lain DATE, DATETIME dan TIME.

        ![w18](https://user-images.githubusercontent.com/114371403/200436803-2b5611df-91c1-48f9-8a12-633efa26caa4.png)

    Kemudian ada juga tipe data lain seperti NULL, yang artinya tipe datanya tidak ada nilai atau kosong. Boolean, tipe data yang mengandung TRUE dan FALSE.

* ### Identifikasi khusus tiap tabel
    - Primary Key
        Setiap tabel yang ada dalam database, harus memiliki tipe data khusus yang mengidentifikasi masing-masing tiap baris. Tipe data yang dimaksud adalah Primary Key. Primary Key sendiri diterapkan pada salah satu kolom saja di dalam tabel dan tipe datanya INT.

        ![w19](https://user-images.githubusercontent.com/114371403/200436806-63500e3e-d762-4576-93ad-431965b091f3.png)

        Biasanya di primary key juga diterapkan AUTO_INCREMENT, yaitu sebuah fungsi yang secara otomatis menambahkan nomor urutan data selanjutnya.

        ![w20](https://user-images.githubusercontent.com/114371403/200436809-d053f2c5-ce84-41a4-a138-8643fd9de719.png)

    - Foreign Key
        Foreign key berguna untuk menghubungkan relasi antar tabel. Biasanya atribut yang foreign key merujuk pada primary key yang tabel nya dihubungkan.

        Cara menghubungkannya adalah dengan menggunakan REFERENCES ke kolom yang ditunjuk.

        ![w21](https://user-images.githubusercontent.com/114371403/200436811-309eb3bc-5266-4f34-8571-133ce0b02765.png)

        FOREIGN KEY di tulis sebagai MUL di dalam struktur database.

        ![w22](https://user-images.githubusercontent.com/114371403/200436817-f8a947ec-53c6-4c85-9bd9-b349847b6fac.png)

* ### JOIN
    Link = https://ngodingdata.com/cara-menggunakan-join-di-mysql/
    JOIN adalah perintah yang berfungsi untuk menggabungkan kolom dan baris dari 2 tabel. Untuk contoh disini kita memiliki 2 tabel dengan isi datanya seperti ini.
    
    Ini adalah tabel mahasiswa.

    ![w23](https://user-images.githubusercontent.com/114371403/200436819-7459324d-779e-4b4a-8b2a-f3a3d1cc1217.png)

    Dan ini adalah tabel transaksi.

    ![w24](https://user-images.githubusercontent.com/114371403/200436822-1d65669d-bbe5-446b-9b23-2f44bc806b0e.png)

    Ada berbagai jenis fungsi JOIN, antara lain :

    - INNER JOIN
        Tipe join ini akan mengambil semua data atau nilai yang ada dalam baris dari tabel pertama dengan nilai dari tabel yang dituju dengan kondisi kedua nya memiliki nilai (tidak NULL).

        ![w25](https://user-images.githubusercontent.com/114371403/200436823-08841a34-5a4c-4b13-a022-64fe593136f5.png)

        ![w26](https://user-images.githubusercontent.com/114371403/200436828-5ab14198-8021-4b78-bcaa-44d664f1ea16.png)

    - LEFT JOIN
        Tipe join ini akan mengambil data dari tabel awal (kiri) dengan tabel yang dituju. Tabel awal akan menampilkan semuanya yang ada di kolom, sedangkan yang dikanan akan juga akan meampilkan data yang ada dalam tabel di awal, walaupun datanya kosong atau NULL.

        ![w27](https://user-images.githubusercontent.com/114371403/200436833-2b37ba07-a1f6-4264-ac7e-31a7296823e5.png)

        ![w28](https://user-images.githubusercontent.com/114371403/200436838-4fea46c6-ee5d-4af2-8520-eb9fb4e3b4be.png)

    - RIGHT JOIN
        Tipe join ini mirip dengan LEFT JOIN, bedanya yang menjadi tabel awalnya adalah yang disebelah kanan.

        ![w29](https://user-images.githubusercontent.com/114371403/200436839-5e513a77-f505-49f8-ad5c-03e2ca40f113.png)

        ![w30](https://user-images.githubusercontent.com/114371403/200436843-3d53b75a-a510-49a7-bec4-87e64d7bc848.png)

* ### Agregate
    Agregate adalah fungsi untuk mengambil data dengan ukuran yang nilai tertentu. Untuk contohnya kita memiliki data seperti dibawah ini.
    
    ![w31](https://user-images.githubusercontent.com/114371403/200436846-7cf3f174-0dfc-4195-aebd-34c23f6c7c81.png)
    
    Fungsi agregate antara lain :
    
    - SUM
        Berfungsi sebagai tambah untuk nilai dari data yang diambil.

        ![w32](https://user-images.githubusercontent.com/114371403/200436849-76f52d11-9184-4534-9989-e3b2116baa97.png)

        ![w33](https://user-images.githubusercontent.com/114371403/200436850-a1f7e617-d086-4883-89ce-d5b1f89dade9.png)

    - MAX
        Berfungsi untuk mengambil data dengan nilai terbesar.

        ![w34](https://user-images.githubusercontent.com/114371403/200436852-7d2deb9e-e0ad-437c-86c5-5267297312ac.png)

        ![w35](https://user-images.githubusercontent.com/114371403/200436856-a4cf3099-3aaa-49b0-b6df-2078ca14b522.png)

    - MIN
        Berfungsi untuk mengambil data dengan nilai terkecil.

        ![w36](https://user-images.githubusercontent.com/114371403/200436861-854f455c-a586-4acf-bc8b-cac4cdab36c1.png)

        ![w37](https://user-images.githubusercontent.com/114371403/200436863-d1aff822-f45f-429e-bc9a-fe2db19fe810.png)

    - COUNT
        Berfungsi untuk menghitung jumlah data yang ada.

        ![w38](https://user-images.githubusercontent.com/114371403/200436868-fb8e3ede-2d01-481e-af9e-4e5ffc638d85.png)

        ![w39](https://user-images.githubusercontent.com/114371403/200436870-8445b30b-cbaf-4ffd-8f5f-73f5dc2ec1ed.png)

* ### UNION
    UNION merupakan fungsi yang akan mengambil data dari kedua tabel, dengan catatan ke 2 tabel memiliki kolom dengan tipe data yang sama.

    ![w40](https://user-images.githubusercontent.com/114371403/200436871-944971bd-6362-4e6e-96dc-0887aec1e31b.png)

    ![w41](https://user-images.githubusercontent.com/114371403/200436872-a72f123d-0a6b-4073-b939-ae3fda044dfc.png)

* ### WHERE, GROUP BY dan HAVING
    - WHERE berfungsi untuk mengambil data dengan mencocokan data yang diminta. Misal kita punya data seperti dibawah ini.

        ![w42](https://user-images.githubusercontent.com/114371403/200436874-05c7f54c-087c-41c2-b6d6-cfb3c2b66707.png)

        Kemuidan kita ingin menampilkan kolom harga dengan kondisi kolom id_barang sama dengan 4.

        ![w43](https://user-images.githubusercontent.com/114371403/200436876-ba5203ef-2df9-4004-9b0a-4ec55df727e6.png)

        Maka kolom harganya akan ditampilkan dengan id_barang ke 4.

        ![w44](https://user-images.githubusercontent.com/114371403/200436877-7cb4df89-bc39-4825-b950-7a899c74a7e1.png)

    - GROUP BY merupakan fungsi untuk mengelompokkan data dalam sebuah kolom yang ditunjuk. Fungsi ini akan menghasilkan kelompok data dengan menghilangkan data yang sama dalam satu tabel. Maka apabila dalam satu kolom terdapat beberapa data yang sama maka data yang akan ditampilkan hanya salah satu.

        Contoh, kita memiliki kolom alamat dengan beberapa data yang sama.

        ![w45](https://user-images.githubusercontent.com/114371403/200436880-df2a984b-4390-44f3-92a4-c5474c177f64.png)

        Kemudian kita ingin menampilkan kolom nama dan nim tetapi berdasarakan group dari kolom alamat. Maka hasilnya data dari kolom alamat yang sama hanya akan diambil atau diwakilkan sekali.

        ![w46](https://user-images.githubusercontent.com/114371403/200436883-40f07dca-9885-4e4b-892e-eb2e08c99190.png)

        ![w47](https://user-images.githubusercontent.com/114371403/200436887-ec69f236-9846-4f14-a055-1bb38cf110ab.png)

    - Kemudian ada HAVING yang sebenarnya memiliki kemiripan dengan WHERE, namun terdapat beberapa perbedaan. WHERE tidak dapat digunakan jika nama kolom nya menggunakan ALIAS, sedangkan HAVING bisa. Kemudian HAVING dapat digunakan pada fungsi agregat sedangkan WHERE tidak bisa.

    Contoh, kita memiliki data seperti berikut.

    ![w48](https://user-images.githubusercontent.com/114371403/200436890-5d0bf35c-82cd-4a4c-96f4-491469641222.png)

    Kita ingin menampilkan kolom id_barang dan harga dan kita ambil datanya berdasarkan kolom jenis, dan juga harga nya lebih dari 20000.

    ![w49](https://user-images.githubusercontent.com/114371403/200436893-bb7aaeab-31b8-4b0a-9edc-ceba9bf7a2f4.png)

    ![w50](https://user-images.githubusercontent.com/114371403/200436895-9d504a90-22f0-454f-b88b-1929fa8b942c.png)

* ### LIKE
    Like biasanya digunakan barengan dengan WHERE, yang fungsinya untuk mencari data dengan kata kunci yang dimasukkan. Nah kata kunci yang dimasukkan didalam query SQL nya kita gunakan "%".

    Contoh, kita memiliki data seperti berikut.

    ![w51](https://user-images.githubusercontent.com/114371403/200436896-fc37052b-8dce-482e-9ffd-7982591b0282.png)

    Kemudian kita ingin mengambil data dari kolom alamat dengan nilai yang sesuai kita input, yaitu "jakarta".

    ![w52](https://user-images.githubusercontent.com/114371403/200436900-c4cbe6a3-3dc6-4ddb-9a99-c775eb4fb638.png)

    ![w53](https://user-images.githubusercontent.com/114371403/200436902-8074f8d5-d6ec-4c8c-8638-c9c0e10b0096.png)

## Authentication dan Authorization

* ### Authentication

    Authentication atau otentikasi adalah proses untuk memverifikasi siapa anda. Hal ini bertujuan untuk mengetahui seseorang dan apakah dapat diberikan akses selanjutnya atau tidak.

    Biasanya cara kerja dari dari otentikasi ada beberapa faktor,seperti :
    
    - Diketahui, yaitu username dan password,
    
    - Kepemilikan, seperti kartu pengenal,

    - Bawaan, seperti sidik jari.

    Otentikasi bisa dimulai dari satu faktor, seperti username dan password. Otentikasi yang hanya melibatkan satu faktor biasanya cukup rentan dari kemanan, oleh karena itu kita bisa melibatkan faktor lain seperti kartu security dan sidik jari. Hal ini disebut multi faktor.

    Biasanya sesi otentikasi dilakukan pada saat masuk atau login. Contoh link nya adalah dengan endpoint login.

    Contoh link = http://localhost:3000/login

    Kita memiliki data akun seperti ini, terdapat id, nama dan password.

    ![w54](https://user-images.githubusercontent.com/114371403/200436905-f38f00c5-1918-40c6-8861-e8366cce577c.png)

    Di codenya kita buat dengan method post karena kita menginputkan data dan dengan endpoint login, kemudian untuk variabel nama dan password kita panggil dari request body. Selanjutnya kita samakan data yang ada dikita yaitu array "users" dengan yang diinput oleh user, yaitu dengan menggunakan "find". Item menunjuk pada array users.

    ![w55](https://user-images.githubusercontent.com/114371403/200436908-1263c2fe-5dad-41d1-84a2-9b64fca6617f.png)

    Kemudian kita buat sesi, jika datanya sesuai maka berhasil dan jika tidak sesuai maka gagal. Kita buat dengan menggunakan if else.

    ![w56](https://user-images.githubusercontent.com/114371403/200436915-c9ac53bc-7ea0-4596-9b2d-36a7312f1648.png)

    Nah disini kita ujinya dengan thunder client. Pertama kita memiliki link yang akan dipakai.

    ![w57](https://user-images.githubusercontent.com/114371403/200436920-00bcd8de-85ed-4020-b07c-1a2bfcef76f1.png)

    Kemudian kita memiliki data yang akan kita uji, dibawah ini adalah data yang sesuai dengan yang kita punya.

    ![w58](https://user-images.githubusercontent.com/114371403/200436921-b2d609db-d94e-4df8-b67c-755dc75fdfb8.png)

    Maka akan menampilkan output berhasil, yaitu if.

    ![w59](https://user-images.githubusercontent.com/114371403/200436923-1057a22d-97a7-4510-8c5c-ae2ab897c353.png)

    Namun jika datanya tidak sesuai seperti dibawah ini.

    ![w60](https://user-images.githubusercontent.com/114371403/200436927-0d847d42-ac75-4ef3-b4c9-92a9b92f30cd.png)

    Maka akan menampilkan output yang gagal, yaitu else.

    ![w61](https://user-images.githubusercontent.com/114371403/200436930-3deae3f0-d865-4956-a7e9-9b98dcc6fdcf.png)

* ### Authorization

    Authorization atau otorisasi adalah hal yang bisa dilakukan user setelah melewati tahap otentikasi. Otorisasi yang diberikan web kepada user bertujuan agar user dapat melakukan hal yang sesuai dengan fungsi website atau programnya. 

    Dengan otorisasi maka user juga lebih mudah dalam mengakses fungsi yang telah dibuat. Selain itu dari segi keamanan ini akan memudahkan pengelola website atau program agar user tidak dapat melakukan hal yang tidak kita inginkan.

    Biasanya sesi otorisasi dilakukan pada saat setelah login dan masuk sebagai role apa, user atau admin. Contoh link nya adalah dengan endpoint users, nama kita, admin atau beranda.

    Contoh link = http://localhost:8080/rezieq_fadillah

* ### Encryption
    Encryption atau enkripsi merupakan sebuah metode yang memformat suatu data menjadi teks yang sengaja agar susah dibaca, baik user maupun sistem. Data yang dienkripsi memiliki tujuan agar data tersebut aman dan tidak dapat diakses oleh pihak lain.

    Untuk melakukan enkripsi kita harus memiliki "kunci" atau key, key ini digunakan untuk mengenkripsi data atau mendekripsi data.

    ![w62](https://user-images.githubusercontent.com/114371403/200436936-b2237a27-40d6-4467-9fe7-72a8e0b5c25d.png)

    Selain metode enkripsi, ada juga metode lain yang disebut Hash. Hash memiliki fungsi yang mirip dengan encryption, namu cara kerjanya yang berbeda. Dalam hash data akan dipecah lagi menjadi beberapa bagian dan tahap, hasilnya kode jadi makin rumit dan sulit untuk dipecahkan.

    Untuk melakukan enkripsi kita membutuhkan JSON Web Token atau disebut juga JWT. Pertama kita perlu menginstall JWT. Jangan lupa kita panggil librarynya.

    ![w63](https://user-images.githubusercontent.com/114371403/200436940-ed0869c0-e29e-4260-b309-0580cf95a157.png)

    Kemudian kita buat KEY, yang akan digunakan oleh tokennya nanti. Data didalam KEY bebas isinya.

    ![w64](https://user-images.githubusercontent.com/114371403/200436942-fdafd6fa-82b4-4d22-b1ca-550f68cad365.png)

    Salah satu penggunaan enkripsi adalah saat melakukan login dan memberikan token. Nama atau email yang diinput user dapat kita enkripsi. Token ini adalah sesuatu yang diberikan kepada user jika berhasil melewati tahap otentikasi. Nah dibawah ini kita tambahkan token ke variabel nama dengan KEY yang kita buat sebelumnya.

    ![w65](https://user-images.githubusercontent.com/114371403/200436947-f57f6063-3719-419f-8032-0bf5237a1ada.png)

    Di sesi jika berhasil login kita panggil tokennya.

    ![w66](https://user-images.githubusercontent.com/114371403/200436949-6b71e4c8-6d87-4ca9-b920-2c4b1ff7d967.png)

    Nah jika user melakukan login dan berhasil maka hasilnya adalah token yang telah kita enkripsi.

    ![w67](https://user-images.githubusercontent.com/114371403/200436951-e10315fd-ba32-4725-8a00-37953c16b05b.png)

## Sequelize
Sequelize adalah Node.js promise-based ORM untuk MySQL, PostgreSQL, SQLite, MSSQL dan database SQL lainnya. Sequelize berfungsi untuk bekerja dengan database dan relasi-relasi di dalamnya. ORM sendiri adalah suatu metode/teknik pemrograman yang digunakan untuk mengkonversi data dari lingkungan bahasa pemrograman berorientasi objek (OOP) dengan lingkungan database relational.

Untuk penerapannya kita perlu menginstall sequelize.

![w68](https://user-images.githubusercontent.com/114371403/200436953-e3e6662b-5744-40af-853b-aef955425e5e.png)

Disini kita inisialisasi nya secara global.

![w69](https://user-images.githubusercontent.com/114371403/200436957-76b75118-a18b-42fc-b092-e4ef43130dff.png)

Kemudian untuk menghubungkan ke databasenya maka kita memerlukan driver SQL nya, dan disini kita install.

![w70](https://user-images.githubusercontent.com/114371403/200436959-abcad2f9-cd19-4c2d-9581-18d74af7d80c.png)

Nah sekarang kita sudah bisa untuk membuat model atau tabelnya. Sebelum itu kita perlu membuat database dahulu diluar, dan di folder config/config.json kita samakan dengan nama database yang kita buat. Disini nama databasenya adalah movie.

![w71](https://user-images.githubusercontent.com/114371403/200436960-76752907-d53b-44ec-aca0-9d6082657f37.png)

Untuk membuat tabel atau model dimulai dari memanggil sequelizenya, kemudian--name "nama model", kemudian atribut atau kolom, "nama kolom":"tipe data".

![w72](https://user-images.githubusercontent.com/114371403/200436963-a82aad64-484b-48bb-831f-e33ae24d04fb.png)

Jika berhasil dibuat maka akan muncul file baru, yaitu di folder migrations dan di folder models, yang akan menampung datanya. Di file ini juga memuat atribute atau kolom dari model yang kita buat.

![w73](https://user-images.githubusercontent.com/114371403/200436964-9bb7ea44-560e-4300-bce3-450642e26b5c.png)

![w74](https://user-images.githubusercontent.com/114371403/200436965-c90805c1-b2c7-4351-a6c8-c7b6eb9a5b0c.png)

Kemudian untuk mengirim model yang kita buat ke database, kita bisa menggunkanan "migrate".

![w75](https://user-images.githubusercontent.com/114371403/200436968-6b5aeb74-b326-4220-8896-db586ecb2da3.png)

Maka datanya akan masuk ke dalam database kita. Kolom id dibuat secara otomatis dan juga auto_increment, kemudian untuk kolom createAt dan updateAt juga dibuat secara default oleh sequelizenya.

![w76](https://user-images.githubusercontent.com/114371403/200436969-b96116ec-f184-4235-b6dc-56338e6d553f.png)
