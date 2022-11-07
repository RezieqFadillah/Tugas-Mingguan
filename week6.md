## Database
Database adalah sebuah tempat yang menyimpan berbagai macam data. Kemudian sistem untuk menyimpan data ini teorganisir dan dapat dibuat bentuk nya sesuai dengan ERD (Entity Relationship). Bentuk dari database ini dari dibuat tersruktur, seperti memiliki tabel, kolom dan baris. Data yang ada dalam database sendiri bisa kita lakukan berbagai macam modifikasi, seperti menambah, mengurangi, mengubah dan menghapus data. 

## MySQL
Dalam membuat database kita membutuhkan sebuah sistem yang dapat meyimpan dan mengopersikan database, yaitu MySQL. MySQL ini dibuat agar dapat digunakan dengan mudah didalam website atau aplikasi apapun itu. 

* ### Perintah MySQL
    Dalam MySQL sub-perintah dibedakan menjadi 3, yaitu DDL, DML dan DCL, namun yang lebih sering digunakan adalah DDL dan DML.

    - DDL (Data Definition Language)
        DDL adalah cara kita dalam membuat struktur database, perintahnya seperti CREATE, ALTER, dan DROP. Contoh penerapannya seperti membuat database, membuat tabel, menambah kolom atau menghapus tabel.

        ![w1](w1.png)

        ![w2](w2.png)

        ![w3](w3.png)

    - DML (Data Manipulation Language)
        DML adalah cara untuk memanipulasi data yang ada di dalam tabel. Data yang dapat dimanipulasi seperti perintah yang dapat diberikan seperti SELECT, INSERT, UPDATE dan DELETE. Contoh penerapan seperti menambahkan data ke kolom, menampilkan data dan mengubah isi baris.

        ![w4](w4.png)

        ![w5](w5.png)

        ![w6](w6.png)

* ### Menampilkan Data
    Ada perintah lain untuk menampilkan data, antara lain :
    - SHOW
        Bisa digunakan untuk menampilkan database ataupun seperti tabel.

        ![w7](w7.png)

        ![w8](w8.png)

    - DESC
        Digunakan untuk menampilkan struktur dari tabel.

        ![w9](w9.png)

        ![w10](w10.png)

    - SELECT
        Digunakan untuk menampilkan nilai yang ada dalam baris. Cara penggunaanya adalah memanggil nama kolom yang ingin ditampilkan.

        ![w11](w11.png)

        ![w12](w12.png)

        Untuk menampikan seluruh data yang ada dalam kolom maka kita gunakan *.

        ![w13](w13.png)

        ![w14](w14.png)

* ### Tipe Data dalam MySQL
    Di MySQL data yang akan disimpan disesuaikan dengan tipe data yang ada. Tipe data ini dibuat agar memudahkan kita dalam mengatur masing-masing tiap jenis data agar mudah dalam mengalokasikan datanya. Nah tipe data yang ada dalam SQL antara lain :

    - Number
        Number berisi kumpulan dengan karakter angka. Jenis-jenisnya antara lain INT dan FLOAT.

        ![w15](w15.png)

        ![w16](w16.png)

    - String
        String berisi kumpulan dengan karakter huruf, angka hingga simbol. Jenis-jenisnya antara lain CHAR, VARCHAR, TEXT dan ENUM.

        ![w17](w17.png)

    - DATE
        Data adalah tipe data yang untuk tanggal. Jenis-jenisnya antara lain DATE, DATETIME dan TIME.

        ![w18](w18.png)

    Kemudian ada juga tipe data lain seperti NULL, yang artinya tipe datanya tidak ada nilai atau kosong. Boolean, tipe data yang mengandung TRUE dan FALSE.

* ### Identifikasi khusus tiap tabel
    - Primary Key
        Setiap tabel yang ada dalam database, harus memiliki tipe data khusus yang mengidentifikasi masing-masing tiap baris. Tipe data yang dimaksud adalah Primary Key. Primary Key sendiri diterapkan pada salah satu kolom saja di dalam tabel dan tipe datanya INT.

        ![w19](w19.png)

        Biasanya di primary key juga diterapkan AUTO_INCREMENT, yaitu sebuah fungsi yang secara otomatis menambahkan nomor urutan data selanjutnya.

        ![w20](w20.png)

    - Foreign Key
        Foreign key berguna untuk menghubungkan relasi antar tabel. Biasanya atribut yang foreign key merujuk pada primary key yang tabel nya dihubungkan.

        Cara menghubungkannya adalah dengan menggunakan REFERENCES ke kolom yang ditunjuk.

        ![w21](w21.png)

        FOREIGN KEY di tulis sebagai MUL di dalam struktur database.

        ![w22](w22.png)

* ### JOIN
    Link = https://ngodingdata.com/cara-menggunakan-join-di-mysql/
    JOIN adalah perintah yang berfungsi untuk menggabungkan kolom dan baris dari 2 tabel. Untuk contoh disini kita memiliki 2 tabel dengan isi datanya seperti ini.
    
    Ini adalah tabel mahasiswa.

    ![w23](w23.png)

    Dan ini adalah tabel transaksi.

    ![w24](w24.png)

    Ada berbagai jenis fungsi JOIN, antara lain :

    - INNER JOIN
        Tipe join ini akan mengambil semua data atau nilai yang ada dalam baris dari tabel pertama dengan nilai dari tabel yang dituju dengan kondisi kedua nya memiliki nilai (tidak NULL).

        ![w25](w25.png)

        ![w26](w26.png)

    - LEFT JOIN
        Tipe join ini akan mengambil data dari tabel awal (kiri) dengan tabel yang dituju. Tabel awal akan menampilkan semuanya yang ada di kolom, sedangkan yang dikanan akan juga akan meampilkan data yang ada dalam tabel di awal, walaupun datanya kosong atau NULL.

        ![w27](w27.png)

        ![w28](w28.png)

    - RIGHT JOIN
        Tipe join ini mirip dengan LEFT JOIN, bedanya yang menjadi tabel awalnya adalah yang disebelah kanan.

        ![w29](w29.png)

        ![w30](w30.png)

* ### Agregate
    Agregate adalah fungsi untuk mengambil data dengan ukuran yang nilai tertentu. Untuk contohnya kita memiliki data seperti dibawah ini.
    
    ![w31](w31.png)
    
    Fungsi agregate antara lain :
    
    - SUM
        Berfungsi sebagai tambah untuk nilai dari data yang diambil.

        ![w32](w32.png)

        ![w33](w33.png)

    - MAX
        Berfungsi untuk mengambil data dengan nilai terbesar.

        ![w34](w34.png)

        ![w35](w35.png)

    - MIN
        Berfungsi untuk mengambil data dengan nilai terkecil.

        ![w36](w36.png)

        ![w37](w37.png)

    - COUNT
        Berfungsi untuk menghitung jumlah data yang ada.

        ![w38](w38.png)

        ![w39](w39.png)

* ### UNION
    UNION merupakan fungsi yang akan mengambil data dari kedua tabel, dengan catatan ke 2 tabel memiliki kolom dengan tipe data yang sama.

    ![w40](w40.png)

    ![w41](w41.png)

* ### WHERE, GROUP BY dan HAVING
    - WHERE berfungsi untuk mengambil data dengan mencocokan data yang diminta. Misal kita punya data seperti dibawah ini.

        ![w42](w42.png)

        Kemuidan kita ingin menampilkan kolom harga dengan kondisi kolom id_barang sama dengan 4.

        ![w43](w43.png)

        Maka kolom harganya akan ditampilkan dengan id_barang ke 4.

        ![w44](w44.png)

    - GROUP BY merupakan fungsi untuk mengelompokkan data dalam sebuah kolom yang ditunjuk. Fungsi ini akan menghasilkan kelompok data dengan menghilangkan data yang sama dalam satu tabel. Maka apabila dalam satu kolom terdapat beberapa data yang sama maka data yang akan ditampilkan hanya salah satu.

        Contoh, kita memiliki kolom alamat dengan beberapa data yang sama.

        ![w45](w45.png)

        Kemudian kita ingin menampilkan kolom nama dan nim tetapi berdasarakan group dari kolom alamat. Maka hasilnya data dari kolom alamat yang sama hanya akan diambil atau diwakilkan sekali.

        ![w46](w46.png)

        ![w47](w47.png)

    - Kemudian ada HAVING yang sebenarnya memiliki kemiripan dengan WHERE, namun terdapat beberapa perbedaan. WHERE tidak dapat digunakan jika nama kolom nya menggunakan ALIAS, sedangkan HAVING bisa. Kemudian HAVING dapat digunakan pada fungsi agregat sedangkan WHERE tidak bisa.

    Contoh, kita memiliki data seperti berikut.

    ![w48](w48.png)

    Kita ingin menampilkan kolom id_barang dan harga dan kita ambil datanya berdasarkan kolom jenis, dan juga harga nya lebih dari 20000.

    ![w49](w49.png)

    ![w50](w50.png)

* ### LIKE
    Like biasanya digunakan barengan dengan WHERE, yang fungsinya untuk mencari data dengan kata kunci yang dimasukkan. Nah kata kunci yang dimasukkan didalam query SQL nya kita gunakan "%".

    Contoh, kita memiliki data seperti berikut.

    ![w51](w51.png)

    Kemudian kita ingin mengambil data dari kolom alamat dengan nilai yang sesuai kita input, yaitu "jakarta".

    ![w52](w52.png)

    ![w53](w53.png)

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

    ![w54](w54.png)

    Di codenya kita buat dengan method post karena kita menginputkan data dan dengan endpoint login, kemudian untuk variabel nama dan password kita panggil dari request body. Selanjutnya kita samakan data yang ada dikita yaitu array "users" dengan yang diinput oleh user, yaitu dengan menggunakan "find". Item menunjuk pada array users.

    ![w55](w55.png)

    Kemudian kita buat sesi, jika datanya sesuai maka berhasil dan jika tidak sesuai maka gagal. Kita buat dengan menggunakan if else.

    ![w56](w56.png)

    Nah disini kita ujinya dengan thunder client. Pertama kita memiliki link yang akan dipakai.

    ![w57](w57.png)

    Kemudian kita memiliki data yang akan kita uji, dibawah ini adalah data yang sesuai dengan yang kita punya.

    ![w58](w58.png)

    Maka akan menampilkan output berhasil, yaitu if.

    ![w59](w59.png)

    Namun jika datanya tidak sesuai seperti dibawah ini.

    ![w60](w60.png)

    Maka akan menampilkan output yang gagal, yaitu else.

    ![w61](w61.png)

* ### Authorization

    Authorization atau otorisasi adalah hal yang bisa dilakukan user setelah melewati tahap otentikasi. Otorisasi yang diberikan web kepada user bertujuan agar user dapat melakukan hal yang sesuai dengan fungsi website atau programnya. 

    Dengan otorisasi maka user juga lebih mudah dalam mengakses fungsi yang telah dibuat. Selain itu dari segi keamanan ini akan memudahkan pengelola website atau program agar user tidak dapat melakukan hal yang tidak kita inginkan.

    Biasanya sesi otorisasi dilakukan pada saat setelah login dan masuk sebagai role apa, user atau admin. Contoh link nya adalah dengan endpoint users, nama kita, admin atau beranda.

    Contoh link = http://localhost:8080/rezieq_fadillah

* ### Encryption
    Encryption atau enkripsi merupakan sebuah metode yang memformat suatu data menjadi teks yang sengaja agar susah dibaca, baik user maupun sistem. Data yang dienkripsi memiliki tujuan agar data tersebut aman dan tidak dapat diakses oleh pihak lain.

    Untuk melakukan enkripsi kita harus memiliki "kunci" atau key, key ini digunakan untuk mengenkripsi data atau mendekripsi data.

    ![w62](w62.png)

    Selain metode enkripsi, ada juga metode lain yang disebut Hash. Hash memiliki fungsi yang mirip dengan encryption, namu cara kerjanya yang berbeda. Dalam hash data akan dipecah lagi menjadi beberapa bagian dan tahap, hasilnya kode jadi makin rumit dan sulit untuk dipecahkan.

    Untuk melakukan enkripsi kita membutuhkan JSON Web Token atau disebut juga JWT. Pertama kita perlu menginstall JWT. Jangan lupa kita panggil librarynya.

    ![w63](w63.png)

    Kemudian kita buat KEY, yang akan digunakan oleh tokennya nanti. Data didalam KEY bebas isinya.

    ![w64](w64.png)

    Salah satu penggunaan enkripsi adalah saat melakukan login dan memberikan token. Nama atau email yang diinput user dapat kita enkripsi. Token ini adalah sesuatu yang diberikan kepada user jika berhasil melewati tahap otentikasi. Nah dibawah ini kita tambahkan token ke variabel nama dengan KEY yang kita buat sebelumnya.

    ![w65](w65.png)

    Di sesi jika berhasil login kita panggil tokennya.

    ![w66](w66.png)

    Nah jika user melakukan login dan berhasil maka hasilnya adalah token yang telah kita enkripsi.

    ![w67](w67.png)

## Sequelize
Sequelize adalah Node.js promise-based ORM untuk MySQL, PostgreSQL, SQLite, MSSQL dan database SQL lainnya. Sequelize berfungsi untuk bekerja dengan database dan relasi-relasi di dalamnya. ORM sendiri adalah suatu metode/teknik pemrograman yang digunakan untuk mengkonversi data dari lingkungan bahasa pemrograman berorientasi objek (OOP) dengan lingkungan database relational.

Untuk penerapannya kita perlu menginstall sequelize.

![w68](w68.png)

Disini kita inisialisasi nya secara global.

![w69](w69.png)

Kemudian untuk menghubungkan ke databasenya maka kita memerlukan driver SQL nya, dan disini kita install.

![w70](w70.png)

Nah sekarang kita sudah bisa untuk membuat model atau tabelnya. Sebelum itu kita perlu membuat database dahulu diluar, dan di folder config/config.json kita samakan dengan nama database yang kita buat. Disini nama databasenya adalah movie.

![w71](w71.png)

Untuk membuat tabel atau model dimulai dari memanggil sequelizenya, kemudian--name "nama model", kemudian atribut atau kolom, "nama kolom":"tipe data".

![w72](w72.png)

Jika berhasil dibuat maka akan muncul file baru, yaitu di folder migrations dan di folder models, yang akan menampung datanya. Di file ini juga memuat atribute atau kolom dari model yang kita buat.

![w73](w73.png)

![w74](w74.png)

Kemudian untuk mengirim model yang kita buat ke database, kita bisa menggunkanan "migrate".

![w75](w75.png)

Maka datanya akan masuk ke dalam database kita. Kolom id dibuat secara otomatis dan juga auto_increment, kemudian untuk kolom createAt dan updateAt juga dibuat secara default oleh sequelizenya.

![w76](w76.png)