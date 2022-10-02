# Week 2
---
## JavaScript
* ### Loop
    Ketika kita ingin menampilkan sebuah data yang banyak, kita bisa menggunakan looping.

    ![loop]([loop.png](https://user-images.githubusercontent.com/114371403/193436185-6833242f-fc17-4d5b-a07d-653a63768f81.png)

    Di atas kita memiliki variable 1 dengan angka 1, kemudian kita akan melakukan perulangan sama dengan kurang dari 5 kali. Selama kondisi tersebut bernilai True, maka data "i" akan terus di tambah hingga bernilai "false".

    ![loop2](https://user-images.githubusercontent.com/114371403/193436186-9a36cc59-6f25-4667-824a-57d0673ce70a.png)
    
    Ada bebera jenis loop dalam JavaScript, antara lain :
    * for, yaitu mengulang sampai dengan batas yang ditentukan, penerapannya seperti contoh disebelumnya.
    * for in, yaitu akan mengulang di dalam sebuah objek dari nilai propertinya. Contohnya, kita memiliki sebuah objek dengan isi seperti properti seperti di bawah ini.

    ![forin](https://user-images.githubusercontent.com/114371403/193436159-00cd2ab9-767d-45b8-bd5d-89c521e8dec2.png)

    Ketika kita jalankan dengan perulangan for in, maka nilai dan properti di dalam objeknya akan di di ambil.

    ![forin2](https://user-images.githubusercontent.com/114371403/193436162-06feb903-251a-405c-a437-f6d2f03da15d.png)

    * while, yaitu dia akan mengulang selama kondisinya bernilai true. Contoh, kita ingin mencari sebuah angka yang dapat dibagi 2 dan 3.

    ![while](https://user-images.githubusercontent.com/114371403/193436208-1172bb14-1d75-4d44-81c2-acb0bea07d25.png)

    Kita juga buat sebuah variable bernilai false, yang digunakan untuk mengulang terus hingga mendapatkan variable nya menjadi true.

    ![while2](https://user-images.githubusercontent.com/114371403/193436210-b090d31c-7389-4a8f-841d-4e87875e01e1.png)

    * do while, mirip seperti while namun ia akan menjalankan perintahnya lebih dulu baru mengecek dengan kondisinya.

    ![dowhile](https://user-images.githubusercontent.com/114371403/193436158-21ef69d1-2909-4384-86e3-2aebb67be624.png)

* ### Function
    Function merupakan sebuah cara atau langkah-langkah yang dibuat dan dapat digunakan atau dipanggil. Membuat sebuah function dimulai dengan deklarasi "function" kemudian nama functionnya dan isi dari functionnya.

    ![fun](https://user-images.githubusercontent.com/114371403/193436170-da1eeb71-b4fb-4282-b7cf-2f9a28dfb52e.png)

    Dari gambar di atas terdapat function dengan nama "namaSaya", kemudian memiliki nilai atau valuenya "Selamat Pagi!" yang dikembalikan ke function dengan return.

    Kita dapat menerapkan banyak hal di dalam function, beberapa di antaranya :
    * Dengan function kita dapat menggunakannya berkali-kali. Contoh, kita ingin menuliskan teks yang sama tapi dengan nama yang berbeda-beda.

    ![fun2](https://user-images.githubusercontent.com/114371403/193436171-4dcb659d-1ffc-4190-8930-4a076b258cf4.png)

    Maka outputnya seperti di bawah ini.

    ![fun3](https://user-images.githubusercontent.com/114371403/193436172-4f4c809b-3583-490a-bd4e-1599e94fecf1.png)

    * Kita juga bisa membuat perulangan di dalam function. Caranya kita hanya perlu mendeklarasikan function, dan di dalam function tersebut kita terapkan looping.

    ![fun4](https://user-images.githubusercontent.com/114371403/193436174-3076c36f-9e15-4dc7-82c1-94fc77ff37c4.png)

    Kita panggil functionnya dan keluar hasilnya.

    ![fun5](https://user-images.githubusercontent.com/114371403/193436175-9157122c-7aac-4806-92ae-5885cd04e697.png)

    ![fun6](https://user-images.githubusercontent.com/114371403/193436176-cc5a9c91-ef98-4564-b81c-be360249c7a8.png)

* ### Scope
    Scope dalam javascript adalah sebuah lokasi dimana sebuah variable dapat diakses. Scope memberi batasan bagaimana sebuah di simpan.
    Terdapat 2 scope, yaitu global dan local :

    * Global scope artinya variable tersebut dapat diakses dari mana saja karena ia ditempatkan di luar blocks.
    * Sedangkan local scope ditempatkan pada area tertentu, seperi function atau looping, sehingga hanya bisa diakses di dalam blocks.

    ![scope](https://user-images.githubusercontent.com/114371403/193436193-bd238d46-7e4f-43f0-8bff-3f96ac998465.png)

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

    ![join](https://user-images.githubusercontent.com/114371403/193436181-d671b054-656f-40ac-9e81-2c14dff8c8d1.png)

    ![join2](https://user-images.githubusercontent.com/114371403/193436184-c309ef2a-56ad-4234-b1c9-d8b0ce583920.png)

    * reverse()

    ![reverse](https://user-images.githubusercontent.com/114371403/193436189-82f76e09-18bb-48a2-9fec-8347090c9efa.png)

    ![reverse2](https://user-images.githubusercontent.com/114371403/193436190-23b4e98d-24ce-441c-8115-d9a6a358ff60.png)
    

---
## DOM
 * ### Pengertian DOM
    DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML. Dengan menggunakan DOM kita dapat melakukan sesuatu terhadap dokumen HTML, seperti mengubah teks, menambahkan data baru dan lain-lain.

* ### Mengakses Element HTML (DOM Property)
    DOM dapat mengakses element yang ada di dalam HTML, jadi element yang ada dalam HTML akan diambil dan ditampilkan.

    Ada beberapa cara untuk mengakses element yang ada di HTML, antara lain :

    * Menggunakan getElement dengan memanggil id, class, atau tag.

    ![title](https://user-images.githubusercontent.com/114371403/193436198-ebead3c8-a799-4e79-8520-daaf0c21f228.png)

    Di atas kita ingin mengakses element yang memiliki id dengan nama "title". Maka outputnya adalah code tersebut akan diambil.

    ![title2](https://user-images.githubusercontent.com/114371403/193436201-55b6ca5e-da99-4fe2-9e3f-b6f76173be07.png)

    Contoh lainnya jika kita jika menggunakan class.

    ![class](https://user-images.githubusercontent.com/114371403/193436148-147afbf5-d84f-4f24-b882-9c257438c14c.png)

    ![class2](https://user-images.githubusercontent.com/114371403/193436149-9c7cc6b7-33c8-478d-88c9-f98a76e3f49b.png)

    Di bawah ini adalah bagian yang menjadi element HTMLnya saat diinspect browser. 

    ![class3](https://user-images.githubusercontent.com/114371403/193436151-dc015741-de56-4ac7-9420-4f6b38d8adbd.png)

    * Untuk mengakses element secara lebih spesifik kita bisa memfilernya dengan selector. Contoh, kita ingin mengakses element dari class item, maka kita gunakan querySelector.

    ![selec](https://user-images.githubusercontent.com/114371403/193436194-f18e6b13-3b10-4f0a-962e-a26c8185c462.png)

    ![selec2](https://user-images.githubusercontent.com/114371403/193436196-9d6a9766-9184-4ef0-92ac-ee1e89c5ea81.png)

* ### Manipulation DOM
    Element yang ada di dalam HTML dapat kita ubah, yaitu dengan DOM manipulation. Caranya adalah dengan kita menggunakan DOM property.

    Beberapa cara memanipulasi element HTML adalah dengan cara menggunakan :
    * innerHTML
    Misal, kita memiliki sebuah teks dari tag < p > seperti di bawah ini.

    ![inner](https://user-images.githubusercontent.com/114371403/193436177-42890f6a-03f8-44ee-a5e6-daad8fe13b79.png)

    ![inner2](https://user-images.githubusercontent.com/114371403/193436178-bf84a816-10c8-49cb-becb-7ef73d7425f0.png)

    Kemudian ingin mengubah element tersebut, caranya adalah dengan kita menggunakan DOM method untuk memanggil elemenet, disini kita gunakan getElementById. Kemudian kita buat variable baru menggunakan DOM property innerHTML.

     ![inner3](https://user-images.githubusercontent.com/114371403/193436179-6b803b37-77b9-4bd2-a214-eef9b61b2373.png)

     Maka hasilnya akan berubah

     ![inner4](https://user-images.githubusercontent.com/114371403/193436180-e5e0eeb5-e916-4d4a-b89e-563950c80e0f.png)

    * createElement
    Kita juga bisa membuat element HTML baru di Javascript. Caranya adalah dengan menggunakan DOM property createElement.

    ![create](https://user-images.githubusercontent.com/114371403/193436153-662de2c5-af35-439f-bd01-2b8b38034f4a.png)

    Maka element yang sebelumnya tidak ada di HTML akan ada.

    ![create2](https://user-images.githubusercontent.com/114371403/193436155-8a85a6f0-e361-44c2-8443-bffb482b8a87.png)

    Hasilnya.

    ![create3](https://user-images.githubusercontent.com/114371403/193436157-4341d09c-0077-4096-a9ef-277f41bad53a.png)

    * remove
    Dengan property remove maka kita menghapus element yang ada di HTML.

    Contoh, kita ingin menghapus element HTML dengan tag Id, maka kita panggil Idnya.

    ![rem](https://user-images.githubusercontent.com/114371403/193436187-0357a296-8e09-4b09-82e6-c49e108a6464.png)

    Maka element HTML dengan Id "tes" akan dihapus.

    * style
    Kita juga dapat mengubah element style yang ada di dalam HTML. Contohnya seperti di bawah ini, kita memiliki sebuah teks yang belum diberikan style.

    ![warna](https://user-images.githubusercontent.com/114371403/193436202-ac5f8fc8-b063-45f8-9fb8-8d506f3882b3.png)

    Kemudian kita masukkan set element stylenya.
    
    ![warna2](https://user-images.githubusercontent.com/114371403/193436204-7fbc662e-62f4-4765-a0ca-74956bd29fcc.png)

    Maka hasilnya adalah seperti ini.

    ![warna3](https://user-images.githubusercontent.com/114371403/193436207-1b0c313f-57f9-4743-b65d-af348495c22e.png)

* ### DOM Event
    DOM Event adalah kejadian atau interaksi yang terjadi pada website. Interaksi yang dihasilkan dapat bermacam-macam, seperti menampilkan pop up window atau mengubah tampilan saat di sentuh.

    Contoh, kita ingin menampilkan sebuah popup window dengan menklik sebuah tombol.

    ![alert](https://user-images.githubusercontent.com/114371403/193436140-92fd3dbc-d116-45d8-924d-92c2ea5b31ec.png)

    Dari code di atas, setelah kita mengambil element id tombol, maka selanjutnya kita buat object yang memiliki event "onclick". Setelah itu kita buat function yang di dalamnya kita gunkaan syntax "alert" untuk menampilkan popup nya.

    ![alert2](https://user-images.githubusercontent.com/114371403/193436143-d540e4cc-dfc8-47d2-8680-a656bd95b126.png)

    Jika tombol "klik saya" di klik maka akan memunculkan popup.

    ![alert3](https://user-images.githubusercontent.com/114371403/193436146-2b0e078f-9666-4170-a968-019a5d7186ec.png)

* ### Form
    Jika kita membuat form input di HTML, maka kita bisa menggunakan JavaScript untuk mengambil data yang diinput.

    Contoh, kita memiliki sebuah form untuk login.

    ![form](https://user-images.githubusercontent.com/114371403/193436163-71eab93f-6b04-4b70-983a-691b1e0065a7.png)

    Kemudian kita buat code di JavaScript dengan DOM property untuk mengambil element di HTML. kita gunakan fungsi addEventListener untuk mengambil data yang ada di HTML, dan juga object dengan properties untuk menyimpan value yang di input.

    ![form2](https://user-images.githubusercontent.com/114371403/193436166-0ed0229a-1f07-4db7-b0a9-fc99efbe4a16.png)

    Ketika user menginput di form seprti ini.

    ![form3](https://user-images.githubusercontent.com/114371403/193436168-4486a345-71ad-4d87-adb3-65519fb58e30.png)

    Maka data yang di input akan diambil oleh JavaScript.

    ![form4](https://user-images.githubusercontent.com/114371403/193436169-52827777-8a6c-4248-846d-9a59a2e8efd1.png)
