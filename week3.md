# Week 3
---
## Array
* ### Pengertian Array
    Array adalah variabel yang dapat menyimpan berbagai tipe data. Urutan dalam isi array disebut index. Index dalam array dimulai dari 0.

    Contoh penerapan array adalah seperti di bawah ini.

    ![array](https://user-images.githubusercontent.com/114371403/194737833-816c5fb6-9e17-4984-b3f3-b76a3e4fead4.png)

    Di atas kita memiliki sebuah variabel "ini_array" yang memiliki 3 data, dengan 2 data string data 1 data integer.

    Jika kita panggil outputnya maka data di array akan ditampilkan.

    ![array2](https://user-images.githubusercontent.com/114371403/194737835-9817758e-495e-49c1-a787-e556f30cf03c.png)

    kita juga bisa melihat panjang isi data array, caranya dengan menggunkan keyword "length".

    ![array6](https://user-images.githubusercontent.com/114371403/194737841-04ec7b26-500e-4460-a5fd-920cac7ba980.png)

    Maka outputnya adalah 3, sesuai dengan banyak data dari arraynya.

    ![array5](https://user-images.githubusercontent.com/114371403/194737839-d2e62425-1133-454d-a343-d06a5031e92a.png)

* ### Mengganti isi array
    Kita juga bisa mengganti isi array dengan data lain, caranya kita panggil variabel arraynya kemudian isi urutan indexnya serta isi data yang ingin diganti.

    ![array3](https://user-images.githubusercontent.com/114371403/194737837-78687b61-aa8b-4307-bfff-f57405d01a32.png)

    Maka data arraynya akan diganti.

    ![array4](https://user-images.githubusercontent.com/114371403/194737838-ba5cd600-dfef-4e74-9323-ddea0cffbe56.png)

* ### Menambah isi array
    Data di dalam array bisa kita tambah. Cara untuk menambah datanya adalah dengan menggunakan push atau unshift.

    * "push" akan menambahkan datanya di akhir array.

        ![tambah1](https://user-images.githubusercontent.com/114371403/194737876-9765e94c-60c8-4002-848f-cdd31bc3a5ed.png)

        Maka data "Unmul" ditambahkan berada di posisi terakhir.

        ![tambah2](https://user-images.githubusercontent.com/114371403/194737877-5c6b8636-8df5-4b3f-b92b-01377f7d3482.png)

    * "unshift" akan menambahkan datanya di awal array.

        ![tambah3](https://user-images.githubusercontent.com/114371403/194737878-c058072b-083b-444b-ae71-5dcb5fc6c2ba.png)

        Maka data "Asik" ditambahkan berada di posisi awal array.

        ![tambah4](https://user-images.githubusercontent.com/114371403/194737880-963c75e6-3acf-4ac4-8a40-9a9ea305c2b0.png)

* ### Menghapus isi array
    Data di dalam array bisa kita hapus. Ada beberapa cara untuk data di dalam array, beberapa di antaranya seperti di bawah ini.

    * "pop" untuk menghapus data di posisi terakhir.

        ![hapus1](https://user-images.githubusercontent.com/114371403/194737842-3deafbcf-19d0-4c2a-9bc3-60456b829538.png)

        Maka hasilnya data terakhir yaitu "Skilvul" di array akan dihapus.

        ![hapus2](https://user-images.githubusercontent.com/114371403/194737844-25e79240-15e9-4512-b9b9-87823e3bb920.png)

    * "shift" untuk menghapus data di awal array.

        ![hapus3](https://user-images.githubusercontent.com/114371403/194737845-fb79c142-bc8a-4d67-b995-8a8776720d41.png)

        Maka hasilnya data "Rezieq" di awal akan dihapus.

        ![hapus4](https://user-images.githubusercontent.com/114371403/194737847-ee435539-ae0e-4d08-8f9c-d86c0e18cf4a.png)

* ### Mengganti dan menghapus data di array
    Ada juga cara untuk menghapus sekaligus mengganti data di array, yaitu dengan menggunakan splice. Cara kerja dari array adalah pertama dengan memasukkan urutan index yang ingin dihapus, kemudian kedua dengan urutan index berikutnya.

    * hapus

        ![splice](https://user-images.githubusercontent.com/114371403/194737869-6b20c0b7-c648-443a-8e59-8bced8ccf252.png)

        Di atas terdapat index ke 0 yang merupakan data yang kita pilih, berikutnya angka 1 yang merujuk pada urutan selanjutnya yang akan di hapus.

        ![splice2](https://user-images.githubusercontent.com/114371403/194737871-ce29ca5b-b83d-4af3-97f9-2f91b6d9177f.png)

    * ganti

        ![splice3](https://user-images.githubusercontent.com/114371403/194737873-8e49b0da-a815-45f4-9539-77ad327a40f3.png)

        Di atas fungsi index pertama dan kedua masih sama, yaitu memlih dan menghapus urutan berikutnya. Bedanya jika ingin menambahkan data baru kita masukkan di index 3. Data "Jokowi" akan menggantikan data yang dihapus.

        ![splice4](https://user-images.githubusercontent.com/114371403/194737875-92376134-d693-4480-ad26-6012fb805e06.png)

* ### Menyalin isi dari array
    Isi dalam array juga bisa disalin, yaitu menggunakan slice. Caranya adalah dengan membuat variabel baru, kemudian kita panggil index dari array yang mau di salin.

    ![slice](https://user-images.githubusercontent.com/114371403/194737866-cc80a4b2-6703-43e5-9e60-51cd21897e75.png)

    Cara kerja dari urutan dalam index di atas sama dengan splice, yaitu dimulai dari index 0, dan index berikutnya merupakan data selanjutnya dari array.

    ![slice2](https://user-images.githubusercontent.com/114371403/194737868-40dd5685-bd66-49cd-98ad-f8536691093a.png)

    Maka data yang diambil adalah array index 0 dan 1.

* ### Menampilkan array menggunakan loop
    Array juga bisa kita tampilkan secara berurutan jika menggunakan loop. Ada beberapa cara menggunakan loop, antara lain :

    * for
        Di dalam for loop kita perlu membuat variabel untuk mengecek isi data di dalam array, di bawah ini variabel tersebut adalah i. Kemudian untuk mengecek apakah variabel tersebut sudah membaca semua variabel kita gunakan tanda kurang ( < ) dari array, arraynya kita tambahkan length untuk membaca panjang isi dari arraynya. Terakhir variabel i kita tambah jika memenuhi kondisi sebelumnya.

        ![loop](https://user-images.githubusercontent.com/114371403/194737848-5e17ce97-189c-46f7-bb13-f7207a15c953.png)

        Setelah semuanya, kita panggil arraynya dengan menyesuaikan kondisi dari variabel i (ini_array[i]).

        ![loop4](https://user-images.githubusercontent.com/114371403/194737852-d7ecca2c-a37a-4558-b0c1-9e3e93a608be.png)

        Maka outputnya seperti di atas.

    * for of
        Mirip seperti for, for of loop akan langsung menampilkan semua isi dari arraynya. Caranya dengan membuat variabel baru dengan mengmabil data dari array yang ingin ditampilkan

        ![loop2](https://user-images.githubusercontent.com/114371403/194737849-cb9e59dd-4609-4026-8f6a-f039bda816ac.png)

        Maka outputnya sama seperti for sebelumnya.

        ![loop4](https://user-images.githubusercontent.com/114371403/194737852-d7ecca2c-a37a-4558-b0c1-9e3e93a608be.png)

    * for each
        for each membaca isi dari array dan menampilkannya secara berurutan tetapi tanpa return, mirip dengan sebelumnya.

        ![loop5](https://user-images.githubusercontent.com/114371403/194737853-0b5ed4c6-f99e-4277-a345-7e1f0a071d7c.png)

        Maka outpunya sama seperti sebelumnya.

        ![loop4](https://user-images.githubusercontent.com/114371403/194737852-d7ecca2c-a37a-4558-b0c1-9e3e93a608be.png)

        Kita juga bisa menggunakan variabel lain yang kita isi datanya dan disesuaikan dengan for each.

        ![loop8](https://user-images.githubusercontent.com/114371403/194737858-53c55381-826d-426f-812e-6b19d4190468.png)

        Di atas, variabel fer kita isi dengan "push" dan dengan mengambil data dari array lain.

        ![loop9](https://user-images.githubusercontent.com/114371403/194737862-bae4c6c6-42b4-41c6-82ba-d0906805dda3.png)

        Maka outputnya seperti di atas.

    * map
        Dengan map kita bisa melakukan perulangan dengan menampilkan atau mengubah data, yaitu dengan menggunakan return.

        ![loop6](https://user-images.githubusercontent.com/114371403/194737856-85e42270-5149-4be0-86c9-97b4e50cdfbf.png)

        Maka data lain seperti teks (Nama = ) akan ditampilkan.

        ![loop7](https://user-images.githubusercontent.com/114371403/194737857-c22e9af0-0c03-45b5-aa41-27028b11da9b.png)

* ### Multi Array
    Kita bisa membuat array yang menyimpan lebih dari 1 list. Jadi di dalam arraynya terdapat array lagi yang lebih dari satu, dan ditampung hanya dengan 1 variabel array.

    ![multi](https://user-images.githubusercontent.com/114371403/194737863-4b9fc043-a95e-423d-896b-ccdadf93f9eb.png)

    Di atas kita memiliki sebuah array "cobaa". Nah di dalam array nya ini terdapat array lagi dengan list yang terpisah.

    Memanggil array di dalamnya dimulai dengan memanggil index listnya, kemudian baru index isi dari listnya.

    ![multi2](https://user-images.githubusercontent.com/114371403/194737865-a590ceee-9a18-463e-bf80-2a873e6b3ecb.png)

    Contoh di atas (Rezieq) kita memanggil index list ke 0, kemudian index ke 0 dari list yang pertama.

* ### Array Object
    Array objek memungkinkan untuk menyimpan sebuah properti yang memiliki value. Kita juga dapat memaggil data yang kita inginkan sesuai dengan objeknya.
    
    * Objek

        ![w1](https://user-images.githubusercontent.com/114371403/194737883-0c3c09ea-a7a4-4b27-a0a3-e8a2146960dd.png)

        Kita memiliki variabel yang menjadi objek dengan nama siswa. Nah di dalam objek siswa ini terdapat properti, dimana properti ini sendiri memiliki data atau value.

        ![w2](https://user-images.githubusercontent.com/114371403/194737885-eda6a44c-5b9a-4d6d-ae9d-198669569e9f.png)

        Jika kita panggil maka akan ditampilkan isi objeknya.

        Kita juga bisa memanggil value dari properti objeknya. Caranya dengan menambahkan propertinya, seperti di bawah ini.

        ![w3](https://user-images.githubusercontent.com/114371403/194737887-2e04b8cc-2003-49ae-b899-d049c063f8d4.png)

        Maka outputnya adalah nilai dari propertinya.

        ![w4](https://user-images.githubusercontent.com/114371403/194737888-d96bf552-8145-46a0-870e-8e2633990187.png)

    * Array Objek
        Mirip seperti objek, dengan array kita bisa menyimpan data objek lebih dari satu.

        ![w5](https://user-images.githubusercontent.com/114371403/194737889-b7f2f7de-85c7-45ee-9686-46ad3d28887e.png)

        Cara memangil objek nya dimulai dengan urutan index nya. Disini kita ada memanggil objek index ke 1 dan juga menampilkan properti hobi.

        ![w6](https://user-images.githubusercontent.com/114371403/194737890-2264c7bc-c551-4dff-a443-84e543e2b199.png)

    * Mengganti nilai dari objek

        Kita bisa mengganti data dari array objek. Caranya dengan memanggil objek beserta urutan indexnya, kemudian propertinya.

        ![w7](https://user-images.githubusercontent.com/114371403/194737891-a90f49d0-d4bb-487f-8080-12ccb922ff85.png)

        Maka nilai dari objek pertama properti nama akan berubah.

        ![w8](https://user-images.githubusercontent.com/114371403/194737893-d7c5e692-a755-4596-83e8-b9dc3e700aca.png)

    * Menambah properti baru

        Properti yang ada di dalam objek bisa kita tambah. Sama seperti cara megganti nilai objek, kita panggil objek beserta indexnya, kemudian nama properti baru nya beserta nilainya. 

        ![w9](https://user-images.githubusercontent.com/114371403/194737896-ec06c744-9b94-455b-a127-9045623686ad.png)

        Maka hasilnya akan ada properti alamat.

        ![w10](https://user-images.githubusercontent.com/114371403/194737897-12aece30-6fe8-4130-8b8f-674f04be7e55.png)

    * Menghapus properti

        Properti di objek bisa kita hapus. Caranya dengan menggunakan keyword delete kemudian nama objek, urutan indexnya dan nama properti yang ingin dihapus.

        ![w11](https://user-images.githubusercontent.com/114371403/194737898-65d76929-3c89-4e06-a85c-f60770b7399e.png)

        Maka propertinya sudah tidak ada.

        ![w12](https://user-images.githubusercontent.com/114371403/194737901-05e7a1a8-10b6-42f4-92d1-88cb015ddf31.png)

* ### Loop for in
    Data di objek bisa ditampilkan dengan loop, yaitu for in.
    Caranya kita buat variabel baru di dalam parameter for, kemudian panggil array yang ingin ditampilkan.

    ![w13](https://user-images.githubusercontent.com/114371403/194737903-d054b8d1-6207-49a3-a9ed-94af0946b7c1.png)

    Maka outputnya seluruh data dari objek akan ditampilkan.

    ![w14](https://user-images.githubusercontent.com/114371403/194737904-cab577b2-7124-4e19-b1d4-e51d99c87a9d.png)

* ### Membuat function didalam objek
    Kita bisa membuat funciton di dalam objek. Functionnya juga bisa kita panggil dan digunakan seperti biasa.

    Caranya kita buat objek seperti biasa, namun di dalam objek tersebut kita buat nama functionya, kemudian isi dari functionnya.

    ![w15](https://user-images.githubusercontent.com/114371403/194737906-8348e00c-c91d-46e0-a04c-7b559a7f665c.png)

    Untuk memanggilnya pertama ketik nama objeknya, kemudian nama functionnya.

    ![w16](https://user-images.githubusercontent.com/114371403/194737907-88c03f5f-f7d2-445d-adbb-bcd1f717d27a.png)

* ### Mengetahui isi jumlah dari array
    Kita bisa mengetahui jumlah index atau value dari objek, yaitu dengan menggunakan objek. Objeknya sendiri ada 2 yaitu index dan value.

    * keys
        Dengan memanggil Object.keys maka kita dapat mengetahui jumlah index dari objek.

        ![w17](https://user-images.githubusercontent.com/114371403/194737908-8e9995b1-a72c-412b-bdae-c74ad5c6249d.png)

        Maka jumlah index dari objeknya akan dtampilkan.

        ![w18](https://user-images.githubusercontent.com/114371403/194737910-4221d360-9dd5-43d6-8377-b7dc7e51f55d.png)

    * values
        Dengan memanggil Object.values maka nilai dari objek nya dapat kita ketahui.

        ![w19](https://user-images.githubusercontent.com/114371403/194737912-d8ad85b6-7a0e-4465-8287-e46cd53e4de0.png)

        Maka nilai atau isi dari objeknya akam ditampilkan.

        ![w20](https://user-images.githubusercontent.com/114371403/194737913-c1bd5092-3aa7-4865-ad11-029ff42690b6.png)
---
## Module
Module adalah sebuah cara untuk menggunakan file javascript yang berbeda dan dihubungkan agar bisa saling diakses.

* ### Menghubungkan javascript dan html dengan
    Untuk mengakses file yang berbeda ini kita perlu mendefinisikan type module saat menghubungkan file html dengan javascript.

    ![w21](https://user-images.githubusercontent.com/114371403/194737914-c7bf1015-8721-41af-9126-6a709c00af3b.png)

    Setelah kita hubungkan maka selanjutnya kita harus mempunyai minimal 2 file javascript, pertama yang dipanggil oleh html, dan kedua untuk menyimpan kode javascriptnya.

    ![w22](https://user-images.githubusercontent.com/114371403/194737915-56c6b2ab-9817-41f1-94c7-8575fbf17ab1.png)

* ### Export dan Import 
    Untuk menghubungkan 2 file javascript yang berbeda, kita gunakan export dan import. Export akan berada di file yang menyediakan kodenya, sedangkan import adalah file yang kita panggil dari file yang kita export. File yang diimport juga merupakan file yang dihubungkan dengan javascript.
        
    Contoh, file export dengan nama jepang.js memiliki source code seperti dibawah ini.

    ![w23](https://user-images.githubusercontent.com/114371403/194737916-3bf45b12-238a-49a4-9e05-b9720cf8f7c2.png)

    Untuk dapat diakses oleh file javascript yang lain, maka kita export code yang ingin diberi akses.

    ![w24](https://user-images.githubusercontent.com/114371403/194737917-e71e7a35-4c2c-4996-bed6-54d944ef2502.png)

    Atau dengan

    ![w244](https://user-images.githubusercontent.com/114371403/194737962-4f3c7faa-0612-4abd-9c6d-0db062ddaa25.png)

    Kemudian di file javascript yang kita hubungkan dengan html, ingin menggunakan source code dari file jepang.js. Cara menghubungkannya kita gunakan import kemudian nama code nya, seperti array, variabel atau function. Serta dari nama file yang diimport (jepang.js)

    ![w25](https://user-images.githubusercontent.com/114371403/194737918-a3f0ad0f-f7b6-4518-b22d-099826ed0159.png)

    Maka datanya bisa ditampilkan.

    ![w255](https://user-images.githubusercontent.com/114371403/194737964-6975fa89-8e73-40fe-91ec-bb90936b9f6f.png)

* ### Memberikan nama alias
    Di file import kita bisa untuk memberikan nama lain dari code yang di import, yaitu dengan memberikan alias "as".

    ![w26](https://user-images.githubusercontent.com/114371403/194737919-cd8b41e1-fa40-4c25-aabf-644cfb7a7595.png)

    atau bisa juga di saat kita import.

    ![w266](https://user-images.githubusercontent.com/114371403/194737967-66b4a17e-4888-4fb9-b95e-8813f8ecc158.png)

    Nama alias bisa kita panggil seperti biasa pada code umumnya.

    ![w27](https://user-images.githubusercontent.com/114371403/194737920-aa41354f-98b1-4095-9fcb-921402b654ff.png)

* ### Export default
    Export default adalah sebuah code yang akan langsung dipanggil jika kita mengimportnya. Export default hanya bisa dilakukan 1x.

    Pertama kita pilih code yang ingin di export secara default.

    ![w28](https://user-images.githubusercontent.com/114371403/194737921-be09bf88-0602-4f92-858e-b2a5988efa4b.png)

    Kemudian kita import nama codenya, maka codenya sudah bisa langsung di akses.

    ![w29](https://user-images.githubusercontent.com/114371403/194737922-637b4202-c262-4408-9bf7-810425c747bc.png)

    ![w30](https://user-images.githubusercontent.com/114371403/194737924-4881c8c5-dc6a-4975-a161-aeadde0e9416.png)

---
## Recursive
Recursive adalah sebuah fungsi yang menjalankan dirinya sendiri. Maksunya dia akan melakukan perulangan ke dirinya sendiri hingga berakhir atau selesai.

Contohnya seperti di bawah ini.

![w31](https://user-images.githubusercontent.com/114371403/194737925-10b7c441-66a7-426e-a855-29af21a4f9d0.png)

Di atas kita memiliki sebuah fungsi yang mana jika data yang di input sama dengan 1 maka program akan berhenti. Namun jika tidak sesuai maka fungsinya akan dipanggil lagi dengan mengurangi jumlahnya. Fungsi ini akan terus berulang hingga datanya sama. Jika sudah sama maka program tidak akan lanjut dan berhenti.

![w32](https://user-images.githubusercontent.com/114371403/194737927-c0dd83d2-cdd9-4cb4-9273-2d6db4b4d925.png)

---
## Synchronous dan Asynchronous
Dalam javascript ada sebuah momen dimana pemrosesan suatu program dilakukan lebih dari 1x. Nah pemrosesan program yang berjalan ini akan kita bahas, dimana ada 2 jenis, yaitu Synchronous dan Asynchronous.

* ### Synchronous
    Ini adalah pemrosesan yang dilakukan secara berurutan, dimana 1 perintah akan dijalankan sampai selesai, dan setelah selesai baru dijalankan perintah berikutnya. Bisa dikatakan synchronous hanya memiliki 1 jalur dan ngeblocking perintah lainnya untuk tetap pada urutannya.

    ![w33](https://user-images.githubusercontent.com/114371403/194737929-27245df4-de40-4291-a3a7-2e79220b6d09.png)

    Contohnya seperti di atas, dimana setiap perintah akan dilakukan secara berurutan dari baris awal. Dimulai dari ngejalankan perintah baris "Pertama", kemudian perintah baris "Kedua", dan terakhir perintah baris "Ketiga".

* ### Asynchronous
    Berbeda dengan sebelumnya yang dijalankan secara berurutan, asynchronous dapat menjalankan perintah lain disaat perintah berikutya sedang dijalankan. Kita dapat memberikan perintah agar pemrosesan data yang lain dijalankan terlebih dahulu, dengan kata lain melompati urutan perintah (non blocking).

    Cara untuk menerapkan asynchronous dengan menggunakan setTimeout. Jadi kita memberi waktu untuk programnya berjalan, nah selama perintahnya berjalan maka perintah yang ada selanjutnya akan melompati perintah yang diberi waktu.

    ![w34](https://user-images.githubusercontent.com/114371403/194737930-cd2ebbdb-d3d0-4bdf-b5e8-88c16e600f87.png)

    Contoh di atas kita membuat perintah "Kedua" dengan memberinya waktu. Selama perintah kedua sedang memproses maka perintah "Ketiga" akan melompati perintah "Kedua".

    ![w35](https://user-images.githubusercontent.com/114371403/194737933-165574b9-5ef9-4aea-8e7a-7513f42cc515.png)

* ### Callback
    Dalam menjalankan asynchronous, perintah yang kita berikan setTimeout akan dilompati oleh perintah berikutnya. Namun kita dapat memanggil kembali perintah tersebut agar sesuai dengan posisi urutannya, yaitu dengan menggunakan fungsi "callback". "callback" akan kita taroh posisinya di parameter fungsi.

    ![w36](https://user-images.githubusercontent.com/114371403/194737934-81f566a9-56c1-4fb6-860e-09b35826c8e8.png)

    Di atas kita terapkan function dengan parameter callback, dimana function nya terdapat setTimeout. Kemudian kita panggil function "dua" dengan parameternya kita isi function "tiga".

    ![w37](https://user-images.githubusercontent.com/114371403/194737935-27f61bf7-a4a2-4702-8ac8-5932ecc80a1d.png)

    Maka hasilnya perintah akan tetap berurutan.

* ### Promise
    Sesuai dengan namanya, promise artinya janji. Dimana perintah akan dijalankan jika kondisinya terpenuhi, namun jika tidak terpenuhi maka akan dijalankan perintah lain.

    Contohnya, kita jalan jika ada uang, kalau kondisi tidak ada uang maka batal jalan.

    ![w38](https://user-images.githubusercontent.com/114371403/194737937-823a84a9-fea7-471b-bede-b998e42714fa.png)

    Parameter resolve digunakan jika kondisi true, jika false maka digunakan reject. Sesuai kondisi di atas, menghasilkan output resolve.

    ![w39](https://user-images.githubusercontent.com/114371403/194737938-75570b56-2cea-497d-8a6a-170f9d84f30c.png)

    Untuk menampilkan hasil dari yang terpenuhi di dalam promise, kita gunakan .then.

    ![w40](https://user-images.githubusercontent.com/114371403/194737939-386ee166-1370-4a8c-a23e-b444ee56ad72.png)

    Maka kondisinya akan ditampilkan.

    ![w41](https://user-images.githubusercontent.com/114371403/194737940-1d304a9a-a9e1-4330-936e-40564d381687.png)

    Jika kita buat kondisinya gagal, maka reject yang akan dijalankan. Namun akan terjadi eror karena program tidak dapat menangkap outputnya.

    ![w42](https://user-images.githubusercontent.com/114371403/194737941-bd2c7f02-5b46-4784-b996-2bf99461b546.png)

    Oleh karena itu kita gunakan .catch untuk memberi tau terdapat eror.

    ![w43](https://user-images.githubusercontent.com/114371403/194737943-6bbcf267-d2f4-4175-aa87-40b274a6fcf0.png)

---
## Web Storage
Saat kita mengunjungi sebuah website, website tersebut bisa menyimpan data yang kita input. Data yang disimpan akan berguna untuk membaca kebiasaan pengguna, seperti hal yang sedang dicari. Untuk menyimpan data di website terdapat cookies. Namun cookies memiliki kekurangan seperti data yang disimpan tidak banyak, memperlambat browser, memiliki tanggal kadaluarsa dan lain-lain. Untuk mengatasi hal tersebut maka kita bisa menggunakan local storage.

* ### Local Storage
    Local storage dapat menyimpan data yang diinput user. Selain itu local storage akan menyimpan data tanpa tanggal kadaluarsa, tidak akan dihapus jika browser ditutup dan dapat menampung hingga 5MB.

    Untuk membuat local storage, pertama kita harus memiliki website yang terdapat input. Dibawah ini adalah form HTMLnya.

    ![w44](https://user-images.githubusercontent.com/114371403/194737945-76a971dc-1020-4a61-be0d-be3ce8369510.png)

    Kemudian dibawah ini adalah file javascriptnya.

    ![w45](https://user-images.githubusercontent.com/114371403/194737947-b00bc437-568f-4374-848b-012c34257395.png)

    Di javascript kita buat array "daftarList" untuk menampung data yang diinput. Kemudian ada getElementById().value untuk mengambil nilai yang diinput, dan juga datanya kita masukkan ke array (push).

    Kita juga perlu mengubah tipe data yang ada di array menjadi string, yaitu dengan JSON.stringify. Terakhir kita masukkan arraynya ke dalam local storage.

    Sekarang akan coba kita input, di bawah ini ada form input yang tadi kita buat dengan modifikasi css.

    ![w46](https://user-images.githubusercontent.com/114371403/194737949-679fd880-5035-47f9-b6b2-b1838fa196d8.png)

    Kemudian kita input datanya, misal di sini kita input "Rezieq".

    ![w47](https://user-images.githubusercontent.com/114371403/194737951-b9d05745-7e3d-4bb3-b292-f1e7fea6786c.png)

    Maka data yang kita input akan masuk ke local storage.

    ![w48](https://user-images.githubusercontent.com/114371403/194737953-33f023d2-5217-4a7d-8a7e-6ab056b451fb.png)

* ### Dark Mode
    Kita bisa membuat tampilan di browser menjadi mode gelap. Pertama-tama kita perlu meyiapkan sebuah css yang memiliki 2 body, 1 untuk mode normal dan 1 lagi untuk mode dark.

    ![w49](https://user-images.githubusercontent.com/114371403/194737956-f7d0189f-5036-43a9-8715-8c580b793b80.png)

    Kemudian kita buat tombol untuk mengganti temanya.

    ![w50](https://user-images.githubusercontent.com/114371403/194737957-d26f6f02-a355-4cfd-adab-ba91db360de8.png)

    Di file javascript kita buat function untuk memanggil tombol di html. Di sini juga kita panggil tema darknya dari local storagenya. Kondisinya akan menyesuaikan, jika terang maka akan menjadi dark dan sebaliknya, jika dark maka akan menjadi terang.

    ![w51](https://user-images.githubusercontent.com/114371403/194737958-d7e7e3fa-4071-4945-aef6-6f3c395b62a6.png)

    Sekarang kita praktek, saat ini tampilan masih normal. Programnya akan memakai style body yang normal.

    ![w52](https://user-images.githubusercontent.com/114371403/194737959-5821ceb8-b765-48de-9ff8-bcda16783697.png)

    Namun saat kita tekan tombolnya, maka tampilannya akan berubah menjadi dark. Programnya akan memakai style body yang dark.

    ![w53](https://user-images.githubusercontent.com/114371403/194737960-80fab072-f9ef-47eb-ade5-8856465d8661.png)
