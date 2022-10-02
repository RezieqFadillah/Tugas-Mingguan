# Week 2
---
## JavaScript
* ### Loop
    Ketika kita ingin menampilkan sebuah data yang banyak, kita bisa menggunakan looping.

    ![loop](loop.png)

    Di atas kita memiliki variable 1 dengan angka 1, kemudian kita akan melakukan perulangan sama dengan kurang dari 5 kali. Selama kondisi tersebut bernilai True, maka data "i" akan terus di tambah hingga bernilai "false".

    ![loop2](loop2.png)
    
    Ada bebera jenis loop dalam JavaScript, antara lain :
    * for, yaitu mengulang sampai dengan batas yang ditentukan, penerapannya seperti contoh disebelumnya.
    * for in, yaitu akan mengulang di dalam sebuah objek dari nilai propertinya. Contohnya, kita memiliki sebuah objek dengan isi seperti properti seperti di bawah ini.

    ![forin](forin.png)

    Ketika kita jalankan dengan perulangan for in, maka nilai dan properti di dalam objeknya akan di di ambil.

    ![forin2](forin2.png)

    * while, yaitu dia akan mengulang selama kondisinya bernilai true. Contoh, kita ingin mencari sebuah angka yang dapat dibagi 2 dan 3.

    ![while](while.png)

    Kita juga buat sebuah variable bernilai false, yang digunakan untuk mengulang terus hingga mendapatkan variable nya menjadi true.

    ![while2](while2.png)

    * do while, mirip seperti while namun ia akan menjalankan perintahnya lebih dulu baru mengecek dengan kondisinya.

    ![dowhile](dowhile.png)

* ### Function
    Function merupakan sebuah cara atau langkah-langkah yang dibuat dan dapat digunakan atau dipanggil. Membuat sebuah function dimulai dengan deklarasi "function" kemudian nama functionnya dan isi dari functionnya.

    ![fun](fun.png)

    Dari gambar di atas terdapat function dengan nama "namaSaya", kemudian memiliki nilai atau valuenya "Selamat Pagi!" yang dikembalikan ke function dengan return.

    Kita dapat menerapkan banyak hal di dalam function, beberapa di antaranya :
    * Dengan function kita dapat menggunakannya berkali-kali. Contoh, kita ingin menuliskan teks yang sama tapi dengan nama yang berbeda-beda.

    ![fun2](fun2.png)

    Maka outputnya seperti di bawah ini.

    ![fun3](fun3.png)

    * Kita juga bisa membuat perulangan di dalam function. Caranya kita hanya perlu mendeklarasikan function, dan di dalam function tersebut kita terapkan looping.

    ![fun4](fun4.png)

    Kita panggil functionnya dan keluar hasilnya.

    ![fun5](fun5.png)

    ![fun6](fun6.png)

* ### Scope
    Scope dalam javascript adalah sebuah lokasi dimana sebuah variable dapat diakses. Scope memberi batasan bagaimana sebuah di simpan.
    Terdapat 2 scope, yaitu global dan local :

    * Global scope artinya variable tersebut dapat diakses dari mana saja karena ia ditempatkan di luar blocks.
    * Sedangkan local scope ditempatkan pada area tertentu, seperi function atau looping, sehingga hanya bisa diakses di dalam blocks.

    ![scope](scope.png)

* ### Method
    Method adalah tindakan yang dapat dilakukan pada objek. Dengan menggunakan method kita dapat melakukan perubahan isi objek. Method dalam JavaScript adalah :
    * join(), untuk menggabungkan element array
    * sort(), untuk mengurutkan element
    * reverse(), untuk membalikan urutan element
    * concat(), untuk menyambungkan array
    * push(), untuk menambahkan element baru
    * pop(), untuk mengurangi element

    Beberapa penerapannya antara lain :
    * join()

    ![join](join.png)

    ![join2](join2.png)

    * reverse()

    ![reverse](reverse.png)

    ![reverse2](reverse2.png)
    

---
## DOM
 * ### Pengertian DOM
    DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML. Dengan menggunakan DOM kita dapat melakukan sesuatu terhadap dokumen HTML, seperti mengubah teks, menambahkan data baru dan lain-lain.

* ### Mengakses Element HTML (DOM Property)
    DOM dapat mengakses element yang ada di dalam HTML, jadi element yang ada dalam HTML akan diambil dan ditampilkan.

    Ada beberapa cara untuk mengakses element yang ada di HTML, antara lain :

    * Menggunakan getElement dengan memanggil id, class, atau tag.

    ![title](title.png)

    Di atas kita ingin mengakses element yang memiliki id dengan nama "title". Maka outputnya adalah code tersebut akan diambil.

    ![title2](title2.png)

    Contoh lainnya jika kita jika menggunakan class.

    ![class](class.png)

    ![class2](class2.png)

    Di bawah ini adalah bagian yang menjadi element HTMLnya saat diinspect browser. 

    ![class3](class3.png)

    * Untuk mengakses element secara lebih spesifik kita bisa memfilernya dengan selector. Contoh, kita ingin mengakses element dari class item, maka kita gunakan querySelector.

    ![selec](selec.png)

    ![selec2](selec2.png)

* ### Manipulation DOM
    Element yang ada di dalam HTML dapat kita ubah, yaitu dengan DOM manipulation. Caranya adalah dengan kita menggunakan DOM property.

    Beberapa cara memanipulasi element HTML adalah dengan cara menggunakan :
    * innerHTML
    Misal, kita memiliki sebuah teks dari tag < p > seperti di bawah ini.

    ![inner](inner.png)

    ![inner2](inner2.png)

    Kemudian ingin mengubah element tersebut, caranya adalah dengan kita menggunakan DOM method untuk memanggil elemenet, disini kita gunakan getElementById. Kemudian kita buat variable baru menggunakan DOM property innerHTML.

     ![inner3](inner3.png)

     Maka hasilnya akan berubah

     ![inner4](inner4.png)

    * createElement
    Kita juga bisa membuat element HTML baru di Javascript. Caranya adalah dengan menggunakan DOM property createElement.

    ![create](create.png)

    Maka element yang sebelumnya tidak ada di HTML akan ada.

    ![create2](create2.png)

    Hasilnya.

    ![create3](create3.png)

    * remove
    Dengan property remove maka kita menghapus element yang ada di HTML.

    Contoh, kita ingin menghapus element HTML dengan tag Id, maka kita panggil Idnya.

    ![rem](rem.png)

    Maka element HTML dengan Id "tes" akan dihapus.

    * style
    Kita juga dapat mengubah element style yang ada di dalam HTML. Contohnya seperti di bawah ini, kita memiliki sebuah teks yang belum diberikan style.

    ![warna](warna.png)

    Kemudian kita masukkan set element stylenya.
    
    ![warna2](warna2.png)

    Maka hasilnya adalah seperti ini.

    ![warna3](warna3.png)

* ### DOM Event
    DOM Event adalah kejadian atau interaksi yang terjadi pada website. Interaksi yang dihasilkan dapat bermacam-macam, seperti menampilkan pop up window atau mengubah tampilan saat di sentuh.

    Contoh, kita ingin menampilkan sebuah popup window dengan menklik sebuah tombol.

    ![alert](alert.png)

    Dari code di atas, setelah kita mengambil element id tombol, maka selanjutnya kita buat object yang memiliki event "onclick". Setelah itu kita buat function yang di dalamnya kita gunkaan syntax "alert" untuk menampilkan popup nya.

    ![alert2](alert2.png)

    Jika tombol "klik saya" di klik maka akan memunculkan popup.

    ![alert3](alert3.png)

* ### Form
    Jika kita membuat form input di HTML, maka kita bisa menggunakan JavaScript untuk mengambil data yang diinput.

    Contoh, kita memiliki sebuah form untuk login.

    ![form](form.png)

    Kemudian kita buat code di JavaScript dengan DOM property untuk mengambil element di HTML. kita gunakan fungsi addEventListener untuk mengambil data yang ada di HTML, dan juga object dengan properties untuk menyimpan value yang di input.

    ![form2](form2.png)

    Ketika user menginput di form seprti ini.

    ![form3](form3.png)

    Maka data yang di input akan diambil oleh JavaScript.

    ![form4](form4.png)