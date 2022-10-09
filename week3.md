# Week 3
---
## Array
* ### Pengertian Array
    Array adalah variabel yang dapat menyimpan berbagai tipe data. Urutan dalam isi array disebut index. Index dalam array dimulai dari 0.

    Contoh penerapan array adalah seperti di bawah ini.

    ![array](array.png)

    Di atas kita memiliki sebuah variabel "ini_array" yang memiliki 3 data, dengan 2 data string data 1 data integer.

    Jika kita panggil outputnya maka data di array akan ditampilkan.

    ![array2](array2.png)

    kita juga bisa melihat panjang isi data array, caranya dengan menggunkan keyword "length".

    ![array6](array6.png)

    Maka outputnya adalah 3, sesuai dengan banyak data dari arraynya.

    ![array5](array5.png)

* ### Mengganti isi array
    Kita juga bisa mengganti isi array dengan data lain, caranya kita panggil variabel arraynya kemudian isi urutan indexnya serta isi data yang ingin diganti.

    ![array3](array3.png)

    Maka data arraynya akan diganti.

    ![array4](array4.png)

* ### Menambah isi array
    Data di dalam array bisa kita tambah. Cara untuk menambah datanya adalah dengan menggunakan push atau unshift.

    * "push" akan menambahkan datanya di akhir array.

        ![tambah1](tambah1.png)

        Maka data "Unmul" ditambahkan berada di posisi terakhir.

        ![tambah2](tambah2.png)

    * "unshift" akan menambahkan datanya di awal array.

        ![tambah3](tambah3.png)

        Maka data "Asik" ditambahkan berada di posisi awal array.

        ![tambah4](tambah4.png)

* ### Menghapus isi array
    Data di dalam array bisa kita hapus. Ada beberapa cara untuk data di dalam array, beberapa di antaranya seperti di bawah ini.

    * "pop" untuk menghapus data di posisi terakhir.

        ![hapus1](hapus1.png)

        Maka hasilnya data terakhir yaitu "Skilvul" di array akan dihapus.

        ![hapus2](hapus2.png)

    * "shift" untuk menghapus data di awal array.

        ![hapus3](hapus3.png)

        Maka hasilnya data "Rezieq" di awal akan dihapus.

        ![hapus4](hapus4.png)

* ### Mengganti dan menghapus data di array
    Ada juga cara untuk menghapus sekaligus mengganti data di array, yaitu dengan menggunakan splice. Cara kerja dari array adalah pertama dengan memasukkan urutan index yang ingin dihapus, kemudian kedua dengan urutan index berikutnya.

    * hapus

        ![splice](splice.png)

        Di atas terdapat index ke 0 yang merupakan data yang kita pilih, berikutnya angka 1 yang merujuk pada urutan selanjutnya yang akan di hapus.

        ![splice2](splice2.png)

    * ganti

        ![splice3](splice3.png)

        Di atas fungsi index pertama dan kedua masih sama, yaitu memlih dan menghapus urutan berikutnya. Bedanya jika ingin menambahkan data baru kita masukkan di index 3. Data "Jokowi" akan menggantikan data yang dihapus.

        ![splice4](splice4.png)

* ### Menyalin isi dari array
    Isi dalam array juga bisa disalin, yaitu menggunakan slice. Caranya adalah dengan membuat variabel baru, kemudian kita panggil index dari array yang mau di salin.

    ![slice](slice.png)

    Cara kerja dari urutan dalam index di atas sama dengan splice, yaitu dimulai dari index 0, dan index berikutnya merupakan data selanjutnya dari array.

    ![slice2](slice2.png)

    Maka data yang diambil adalah array index 0 dan 1.

* ### Menampilkan array menggunakan loop
    Array juga bisa kita tampilkan secara berurutan jika menggunakan loop. Ada beberapa cara menggunakan loop, antara lain :

    * for
        Di dalam for loop kita perlu membuat variabel untuk mengecek isi data di dalam array, di bawah ini variabel tersebut adalah i. Kemudian untuk mengecek apakah variabel tersebut sudah membaca semua variabel kita gunakan tanda kurang ( < ) dari array, arraynya kita tambahkan length untuk membaca panjang isi dari arraynya. Terakhir variabel i kita tambah jika memenuhi kondisi sebelumnya.

        ![loop](loop.png)

        Setelah semuanya, kita panggil arraynya dengan menyesuaikan kondisi dari variabel i (ini_array[i]).

        ![loop4](loop4.png)

        Maka outputnya seperti di atas.

    * for of
        Mirip seperti for, for of loop akan langsung menampilkan semua isi dari arraynya. Caranya dengan membuat variabel baru dengan mengmabil data dari array yang ingin ditampilkan

        ![loop2](loop2.png)

        Maka outputnya sama seperti for sebelumnya.

        ![loop4](loop4.png)

    * for each
        for each membaca isi dari array dan menampilkannya secara berurutan tetapi tanpa return, mirip dengan sebelumnya.

        ![loop5](loop5.png)

        Maka outpunya sama seperti sebelumnya.

        ![loop4](loop4.png)

        Kita juga bisa menggunakan variabel lain yang kita isi datanya dan disesuaikan dengan for each.

        ![loop8](loop8.png)

        Di atas, variabel fer kita isi dengan "push" dan dengan mengambil data dari array lain.

        ![loop9](loop9.png)

        Maka outputnya seperti di atas.

    * map
        Dengan map kita bisa melakukan perulangan dengan menampilkan atau mengubah data, yaitu dengan menggunakan return.

        ![loop6](loop6.png)

        Maka data lain seperti teks (Nama = ) akan ditampilkan.

        ![loop7](loop7.png)

* ### Multi Array
    Kita bisa membuat array yang menyimpan lebih dari 1 list. Jadi di dalam arraynya terdapat array lagi yang lebih dari satu, dan ditampung hanya dengan 1 variabel array.

    ![multi](multi.png)

    Di atas kita memiliki sebuah array "cobaa". Nah di dalam array nya ini terdapat array lagi dengan list yang terpisah.

    Memanggil array di dalamnya dimulai dengan memanggil index listnya, kemudian baru index isi dari listnya.

    ![multi](multi2.png)

    Contoh di atas (Rezieq) kita memanggil index list ke 0, kemudian index ke 0 dari list yang pertama.

* ### Array Object
    Array objek memungkinkan untuk menyimpan sebuah properti yang memiliki value. Kita juga dapat memaggil data yang kita inginkan sesuai dengan objeknya.
    
    * Objek

        ![w1](w1.png)

        Kita memiliki variabel yang menjadi objek dengan nama siswa. Nah di dalam objek siswa ini terdapat properti, dimana properti ini sendiri memiliki data atau value.

        ![w2](w2.png)

        Jika kita panggil maka akan ditampilkan isi objeknya.

        Kita juga bisa memanggil value dari properti objeknya. Caranya dengan menambahkan propertinya, seperti di bawah ini.

        ![w3](w3.png)

        Maka outputnya adalah nilai dari propertinya.

        ![w4](w4.png)

    * Array Objek
        Mirip seperti objek, dengan array kita bisa menyimpan data objek lebih dari satu.

        ![w5](w5.png)

        Cara memangil objek nya dimulai dengan urutan index nya. Disini kita ada memanggil objek index ke 1 dan juga menampilkan properti hobi.

        ![w6](w6.png)

    * Mengganti nilai dari objek

        Kita bisa mengganti data dari array objek. Caranya dengan memanggil objek beserta urutan indexnya, kemudian propertinya.

        ![w7](w7.png)

        Maka nilai dari objek pertama properti nama akan berubah.

        ![w8](w8.png)

    * Menambah properti baru

        Properti yang ada di dalam objek bisa kita tambah. Sama seperti cara megganti nilai objek, kita panggil objek beserta indexnya, kemudian nama properti baru nya beserta nilainya. 

        ![w9](w9.png)

        Maka hasilnya akan ada properti alamat.

        ![w10](w10.png)

    * Menghapus properti

        Properti di objek bisa kita hapus. Caranya dengan menggunakan keyword delete kemudian nama objek, urutan indexnya dan nama properti yang ingin dihapus.

        ![w11](w11.png)

        Maka propertinya sudah tidak ada.

        ![w12](w12.png)

* ### Loop for in
    Data di objek bisa ditampilkan dengan loop, yaitu for in.
    Caranya kita buat variabel baru di dalam parameter for, kemudian panggil array yang ingin ditampilkan.

    ![w13](w13.png)

    Maka outputnya seluruh data dari objek akan ditampilkan.

    ![w14](w14.png)

* ### Membuat function didalam objek
    Kita bisa membuat funciton di dalam objek. Functionnya juga bisa kita panggil dan digunakan seperti biasa.

    Caranya kita buat objek seperti biasa, namun di dalam objek tersebut kita buat nama functionya, kemudian isi dari functionnya.

    ![w15](w15.png)

    Untuk memanggilnya pertama ketik nama objeknya, kemudian nama functionnya.

    ![w16](w16.png)

* ### Mengetahui isi jumlah dari array
    Kita bisa mengetahui jumlah index atau value dari objek, yaitu dengan menggunakan objek. Objeknya sendiri ada 2 yaitu index dan value.

    * keys
        Dengan memanggil Object.keys maka kita dapat mengetahui jumlah index dari objek.

        ![w17](w17.png)

        Maka jumlah index dari objeknya akan dtampilkan.

        ![w18](w18.png)

    * values
        Dengan memanggil Object.values maka nilai dari objek nya dapat kita ketahui.

        ![w19](w19.png)

        Maka nilai atau isi dari objeknya akam ditampilkan.

        ![w20](w20.png)
---
## Module
Module adalah sebuah cara untuk menggunakan file javascript yang berbeda dan dihubungkan agar bisa saling diakses.

* ### Menghubungkan javascript dan html dengan
    Untuk mengakses file yang berbeda ini kita perlu mendefinisikan type module saat menghubungkan file html dengan javascript.

    ![w21](w21.png)

    Setelah kita hubungkan maka selanjutnya kita harus mempunyai minimal 2 file javascript, pertama yang dipanggil oleh html, dan kedua untuk menyimpan kode javascriptnya.

    ![w22](w22.png)

* ### Export dan Import 
    Untuk menghubungkan 2 file javascript yang berbeda, kita gunakan export dan import. Export akan berada di file yang menyediakan kodenya, sedangkan import adalah file yang kita panggil dari file yang kita export. File yang diimport juga merupakan file yang dihubungkan dengan javascript.
        
    Contoh, file export dengan nama jepang.js memiliki source code seperti dibawah ini.

    ![w23](w23.png)

    Untuk dapat diakses oleh file javascript yang lain, maka kita export code yang ingin diberi akses.

    ![w24](w24.png)

    Atau dengan

    ![w244](w244.png)

    Kemudian di file javascript yang kita hubungkan dengan html, ingin menggunakan source code dari file jepang.js. Cara menghubungkannya kita gunakan import kemudian nama code nya, seperti array, variabel atau function. Serta dari nama file yang diimport (jepang.js)

    ![w25](w25.png)

    Maka datanya bisa ditampilkan.

    ![w255](w255.png)

* ### Memberikan nama alias
    Di file import kita bisa untuk memberikan nama lain dari code yang di import, yaitu dengan memberikan alias "as".

    ![w26](w26.png)

    atau bisa juga di saat kita import.

    ![w266](w266.png)

    Nama alias bisa kita panggil seperti biasa pada code umumnya.

    ![w27](w27.png)

* ### Export default
    Export default adalah sebuah code yang akan langsung dipanggil jika kita mengimportnya. Export default hanya bisa dilakukan 1x.

    Pertama kita pilih code yang ingin di export secara default.

    ![w28](w28.png)

    Kemudian kita import nama codenya, maka codenya sudah bisa langsung di akses.

    ![w29](w29.png)

    ![w30](w30.png)

---
## Recursive
Recursive adalah sebuah fungsi yang menjalankan dirinya sendiri. Maksunya dia akan melakukan perulangan ke dirinya sendiri hingga berakhir atau selesai.

Contohnya seperti di bawah ini.

![w31](w31.png)

Di atas kita memiliki sebuah fungsi yang mana jika data yang di input sama dengan 1 maka program akan berhenti. Namun jika tidak sesuai maka fungsinya akan dipanggil lagi dengan mengurangi jumlahnya. Fungsi ini akan terus berulang hingga datanya sama. Jika sudah sama maka program tidak akan lanjut dan berhenti.

![w32](w32.png)

---
## Synchronous dan Asynchronous
Dalam javascript ada sebuah momen dimana pemrosesan suatu program dilakukan lebih dari 1x. Nah pemrosesan program yang berjalan ini akan kita bahas, dimana ada 2 jenis, yaitu Synchronous dan Asynchronous.

* ### Synchronous
    Ini adalah pemrosesan yang dilakukan secara berurutan, dimana 1 perintah akan dijalankan sampai selesai, dan setelah selesai baru dijalankan perintah berikutnya. Bisa dikatakan synchronous hanya memiliki 1 jalur dan ngeblocking perintah lainnya untuk tetap pada urutannya.

    ![w33](w33.png)

    Contohnya seperti di atas, dimana setiap perintah akan dilakukan secara berurutan dari baris awal. Dimulai dari ngejalankan perintah baris "Pertama", kemudian perintah baris "Kedua", dan terakhir perintah baris "Ketiga".

* ### Asynchronous
    Berbeda dengan sebelumnya yang dijalankan secara berurutan, asynchronous dapat menjalankan perintah lain disaat perintah berikutya sedang dijalankan. Kita dapat memberikan perintah agar pemrosesan data yang lain dijalankan terlebih dahulu, dengan kata lain melompati urutan perintah (non blocking).

    Cara untuk menerapkan asynchronous dengan menggunakan setTimeout. Jadi kita memberi waktu untuk programnya berjalan, nah selama perintahnya berjalan maka perintah yang ada selanjutnya akan melompati perintah yang diberi waktu.

    ![w34](w34.png)

    Contoh di atas kita membuat perintah "Kedua" dengan memberinya waktu. Selama perintah kedua sedang memproses maka perintah "Ketiga" akan melompati perintah "Kedua".

    ![w35](w35.png)

* ### Callback
    Dalam menjalankan asynchronous, perintah yang kita berikan setTimeout akan dilompati oleh perintah berikutnya. Namun kita dapat memanggil kembali perintah tersebut agar sesuai dengan posisi urutannya, yaitu dengan menggunakan fungsi "callback". "callback" akan kita taroh posisinya di parameter fungsi.

    ![w36](w36.png)

    Di atas kita terapkan function dengan parameter callback, dimana function nya terdapat setTimeout. Kemudian kita panggil function "dua" dengan parameternya kita isi function "tiga".

    ![w37](w37.png)

    Maka hasilnya perintah akan tetap berurutan.

* ### Promise
    Sesuai dengan namanya, promise artinya janji. Dimana perintah akan dijalankan jika kondisinya terpenuhi, namun jika tidak terpenuhi maka akan dijalankan perintah lain.

    Contohnya, kita jalan jika ada uang, kalau kondisi tidak ada uang maka batal jalan.

    ![w38](w38.png)

    Parameter resolve digunakan jika kondisi true, jika false maka digunakan reject. Sesuai kondisi di atas, menghasilkan output resolve.

    ![w39](w39.png)

    Untuk menampilkan hasil dari yang terpenuhi di dalam promise, kita gunakan .then.

    ![w40](w40.png)

    Maka kondisinya akan ditampilkan.

    ![w41](w41.png)

    Jika kita buat kondisinya gagal, maka reject yang akan dijalankan. Namun akan terjadi eror karena program tidak dapat menangkap outputnya.

    ![w42](w42.png)

    Oleh karena itu kita gunakan .catch untuk memberi tau terdapat eror.

    ![w43](w43.png)

---
## Web Storage
Saat kita mengunjungi sebuah website, website tersebut bisa menyimpan data yang kita input. Data yang disimpan akan berguna untuk membaca kebiasaan pengguna, seperti hal yang sedang dicari. Untuk menyimpan data di website terdapat cookies. Namun cookies memiliki kekurangan seperti data yang disimpan tidak banyak, memperlambat browser, memiliki tanggal kadaluarsa dan lain-lain. Untuk mengatasi hal tersebut maka kita bisa menggunakan local storage.

* ### Local Storage
    Local storage dapat menyimpan data yang diinput user. Selain itu local storage akan menyimpan data tanpa tanggal kadaluarsa, tidak akan dihapus jika browser ditutup dan dapat menampung hingga 5MB.

    Untuk membuat local storage, pertama kita harus memiliki website yang terdapat input. Dibawah ini adalah form HTMLnya.

    ![w44](w44.png)

    Kemudian dibawah ini adalah file javascriptnya.

    ![w45](w45.png)

    Di javascript kita buat array "daftarList" untuk menampung data yang diinput. Kemudian ada getElementById().value untuk mengambil nilai yang diinput, dan juga datanya kita masukkan ke array (push).

    Kita juga perlu mengubah tipe data yang ada di array menjadi string, yaitu dengan JSON.stringify. Terakhir kita masukkan arraynya ke dalam local storage.

    Sekarang akan coba kita input, di bawah ini ada form input yang tadi kita buat dengan modifikasi css.

    ![w46](w46.png)

    Kemudian kita input datanya, misal di sini kita input "Rezieq".

    ![w47](w47.png)

    Maka data yang kita input akan masuk ke local storage.

    ![w48](w48.png)

* ### Dark Mode
    Kita bisa membuat tampilan di browser menjadi mode gelap. Pertama-tama kita perlu meyiapkan sebuah css yang memiliki 2 body, 1 untuk mode normal dan 1 lagi untuk mode dark.

    ![w49](w49.png)

    Kemudian kita buat tombol untuk mengganti temanya.

    ![w50](w50.png)

    Di file javascript kita buat function untuk memanggil tombol di html. Di sini juga kita panggil tema darknya dari local storagenya. Kondisinya akan menyesuaikan, jika terang maka akan menjadi dark dan sebaliknya, jika dark maka akan menjadi terang.

    ![w51](w51.png)

    Sekarang kita praktek, saat ini tampilan masih normal. Programnya akan memakai style body yang normal.

    ![w52](w52.png)

    Namun saat kita tekan tombolnya, maka tampilannya akan berubah menjadi dark. Programnya akan memakai style body yang dark.

    ![w53](w53.png)