# Week 1
---
## Unix Command Line
* ### Command Line Interface (CLI)
    Command Line Interface atau disingat CLI adalah sebuah program untuk mengakses sistem dengan perintah yang kita berikan.
* ### Shell
    Untuk menghubungkan kita dengan sistem, maka kita membutuhkan sebuah teks program, yaitu Shell. Shell akan berisi sebuah perintah yang akan dijalankan oleh sistem.
* ### Terminal
    Terminal merupakan sebuah aplikasi yang membantu kita terhubung dengan shell, disinilah kita memasukkan kode atau perintah.
* ### Struktur Sistem
    Struktur di sini mengatur posisi di mana data yang berada di sistem disimpan sesuai dengan lokasinya. Gambaran strukturnya seperti dibawah ini.
    
    ![unix](https://user-images.githubusercontent.com/114371403/192682902-6c718906-cdc5-4447-a66d-f468f838251c.png)

* ### Commad
    Dalam mengakses command line interface dengan shell di terminal, terdapat kode perintah, diantaranya :
    * pwd, untuk melihat directory saat ini
    * cd, untuk pindah directory
    * ls, untuk melihat isi dari directory
    * touch, untuk membuat sebuah file baru
    * cp, untuk menyalin file
    * mv, untuk memindahkan file atau directory
    * rm, untuk menghapus file atau directory
---
## Git dan GitHub
* ### Git
    Git adalah sebuah program yang dapat melacak sebuah project yang disimpan lengkap dengan alur perubahannya.

* ### GitHub
    GitHub berguna untuk menyimpan source code dari suatu proyek dan melacak riwayat lengkap semua perubahan kode itu. Dengan adanya fitur seperti ini, maka penggunaan git akan sangat membantu banyak orang dalam belajar membuat sebuah program juga.

* ### Penggunaan Git
    Di sini kita menggunakan software Git Bash untuk menjalankan programnya. Penggunaan git seperti gambar di bawah ini :
    
    ![git](https://user-images.githubusercontent.com/114371403/192683314-0d2b9255-882e-4bf0-a96b-1fc98a9101ff.png)
    Kemudian untuk perintah yang berada di dalam git antara lain :
    * git init, untuk membuat repository.
    * git status, untuk mengecek apakah terjadi perubahan atau tidak.
    * git add, untuk menambahkan file yang telah di ubah di git.
    * git remote, untuk menghubungkan remote repository denngan project lokal dari direktori yang kita buat.
    * git commit -m, untuk menyimpan perubahan pada git.
    * git push origin, untuk mengirimkan perubahan ke remote repository.
    * git branch -b, untuk membuat branch baru.
    * git checkout, untuk berpindah branch.
    * git merge, untuk menggabungkan branch cabang ke branch master.
---
## HTML
* ### Pengertian HTML
    HTML adalah sebuah bahasa yang komputer untuk membuat sebuah kerangka dari sebuah website yang dapat diakses dari browser. HTML sendiri berisi sebuah code-code yang akan ditampilkan dalam sebuah website.
* ### Kerangka HTML
    Ini adalah gambaran kerangka HTML.
    
    ![kerangka](https://user-images.githubusercontent.com/114371403/192683329-e48a4289-e0d5-4071-a967-acc6a1939e64.png)

* ### Element
    Element di sebuah web dapat berupa teks, judul, gambar, video dan lain-lain.
    
    ![element](https://user-images.githubusercontent.com/114371403/192683286-effe7b09-4006-45f4-b093-0be2db2fd2b0.png)
    Dari gambar di atas, element terdiri dari :
    * opening tag (< p >) sebagai tag pembuka, dan closing tag (< /p >) sebagai tag penutup
    * Attribute (style) yang digunakan untuk memberi desain, mengirim link (href), atau mengambil file (src)
    * value (color=blue) sebagai nilai dari attribute
    * content (Rezieq) merupakan isi dari tag yang ingin ditampilkan

* ### Tag
    Tag merupakan sebuah kode atau sintaks dengan fungsi perintah tertentu. Tag diawali dengan tag pembuka yang berada di bagian depan dan tag penutup yang berada di bagian terakhir.
    
    Di kerangka HTML sebelumnya terlihat beberapa tag, seperti tag < html > untuk membuat mendefinisikan website "html", kemudian tag < head > untuk menyisipkan perintah seperti menghubungkan dengan file lain (css dan javascript), tag < title > untuk membuat judul dari website dan tag "body" untuk memasukkan sintaks utama dari halaman website yang kita buat.

    Selain itu terdapat banyak penggunaan tag lain seperti :
    * Heading < h1 > untuk membuat teks tebal

    ![heading](https://user-images.githubusercontent.com/114371403/192683316-1a886ed3-89dd-49e2-a558-0a4877f92ba2.png)
    * paraghraf < p > untuk membuat kalimat

    ![paragraf](https://user-images.githubusercontent.com/114371403/192683369-21f00ae2-38f2-4d3c-a806-116a8dcb2406.png)
    * link < a > untuk mengarahkan ke suatu website

    ![link](https://user-images.githubusercontent.com/114371403/192683352-fe7151b8-5b0c-4550-a2a1-598926e9809c.png)
    * div < div > untuk memberi batasan
    * table < table > untuk membuat sebuah tabel

    ![tabel](https://user-images.githubusercontent.com/114371403/192683379-1b8d57b1-95eb-46a1-a3dd-bfdd9de58ebf.png)
    * image < image > untuk menampilkan foto
    * video < video > untuk menampilkan video

* ### Form
    Di HTML kita bisa menginputkan sebuah data, nah data-data yang kita inputkan bisa dikelompokan di dalam tag < form >. 
    
    * Di tag < form > ini kita bisa menambahkan tag < input > untuk memasukkan data teks, seperti nama, alamat, nomor hp dan lain-lain.
    Ini sintaks nya :
    
    ![input2](https://user-images.githubusercontent.com/114371403/192683326-77a55c8b-b904-4adf-9d98-3d8cbf582536.png)
    Output :
    
    ![input](https://user-images.githubusercontent.com/114371403/192683322-03d6766f-d71b-4029-9331-cea62d8bab8a.png)
    * Kemudian ada tag < option > yang digunakan untuk memilih beberapa pilihan, biasa juga dibarengi dengan tag < select >.
    Ini sintaks nya :
    
    ![option2](https://user-images.githubusercontent.com/114371403/192683366-908f51ea-e4d9-4d37-a430-9ef7c162dbf7.png)
    Output :
    
    ![option](https://user-images.githubusercontent.com/114371403/192683364-f424e6c2-f721-4b73-9d7d-62560a113574.png)

    * Kemudian ada tag < textarea > untuk menginput sebuah kalimat yang panjang.
    Ini sintaks nya :
    
    ![textarea2](https://user-images.githubusercontent.com/114371403/192683392-8a98e3d3-51e4-4c7c-bf2c-1d3548ec685a.png)
    Output :
    
    ![textarea](https://user-images.githubusercontent.com/114371403/192683384-627e4a67-5282-4cf0-986b-6a4363e0299d.png)

    * Kemudian ada tag < button > yang berfungsi sebagai tombol untuk mensubmit data atau form yang telah kita input sebelumnya.
    Ini sintaks nya :
    
    ![button2](https://user-images.githubusercontent.com/114371403/192683283-2c88dd21-9e2e-48c5-b393-52399ba109c5.png)
    Output :
    
    ![button](https://user-images.githubusercontent.com/114371403/192683280-1e852f4e-399f-4af6-902a-0f7988f0c3fe.png)

---
## CSS
* ### Pengertian CSS
    CSS atau kepanjangan dari Cascading Style Sheets adalah sebuah bahasa komputer yang digunakan untuk mendesain sebuah website.
* ### Penerapan  CSS
    CSS dapat diterapkan dengan berbagai cara, diantaranya :
    * Inline, yaitu langsung memasukkan CSS nya di dalam tag HTML.

    ![inline](https://user-images.githubusercontent.com/114371403/192683321-102110e9-9361-4444-898e-0e50be8547a3.png)
    * Internal, sebuah element style yang kita buat di satu halaman atau file dengan HTML.

    ![internal](https://user-images.githubusercontent.com/114371403/192683327-ac5a4cca-ee3a-4eb9-81ad-e212a02a3c0f.png)
    * External, merupakan file CSS yang terpisah dengan HTML. Kita dapat menghubungkannya dengan menggunakan link.

    ![external](https://user-images.githubusercontent.com/114371403/192683289-4a9f4446-58a3-4e23-8207-d7f9c0dd4d83.png)
* ### Penulisan CSS
    Penulisan CSS terdiri dari :
    
    ![penulisan](https://user-images.githubusercontent.com/114371403/192683372-57d09560-547f-4f86-b5cb-c3e46aefe592.png)
    * Selector, yaitu target yang ingin kita beri desain.
    * Properti, yaitu jenis desain yang ingin diterapkan.
    * Value, merupakan nilai yang dimasukkan dari properti, seperti warna, tinggi dan ukuran teks.
* ### Box Model
    Di dalam mendesain website, ada batasan di area tertentu yang harus di pahami, di antaranya :
    * Margin, yaitu area terluar.
    * Border, yaitu garis tepi.
    * Padding, yaitu area kosong.
    * Content, isi utama dari sebuah website. Seperti teks, foto, video dan lain-lain.

    ![box_model](https://user-images.githubusercontent.com/114371403/192683278-5c7ceb75-8a87-498b-a56f-93b84e0b8474.png)

* ### Kerja CSS
    Kode-kode atau sintaks dari CSS cukup beragam dan juga penerapannya akan langsung terlihat. Masing-masing dari setiap kode CSS yang dideklarasikan akan saling mempengaruhi satu sama lain.
    Contoh, kita memiliki 2 buah style, yang pertama inline :
    
    ![kerja2](https://user-images.githubusercontent.com/114371403/192683335-b94de807-5df7-4af5-a411-a0702e66145a.png)
    Kemudian yang kedua external :
    
    ![kerja3](https://user-images.githubusercontent.com/114371403/192683340-6a7f0373-0e51-49de-9703-646fbc5b85e6.png)
    Jika keduanya digabungkan maka hasilnya :
    
    ![kerja](https://user-images.githubusercontent.com/114371403/192683332-182dbb41-6274-4243-a4c9-72aa17d94f7c.png)
    
* ### Flex Box
    Flex Box berguna untuk mengatur layout, posisi dan ukuran dari tiap elementnya. Dalam flex box terdapat istilah :
    * container, yang menjadi pembungkus dan mengatur tampilan dari element.
    * item, element yang ada di dalam container.
    Berikut adalah contoh codenya.
    
    ![felxx2](https://user-images.githubusercontent.com/114371403/192683298-6fa4cc71-30ce-44d0-9595-abd10bb167dd.png)
    Akan menampilkan :
    
    ![felxx](https://user-images.githubusercontent.com/114371403/192683295-81ac3882-b4a5-47da-8cdc-ed6109345eba.png)
    Kemudian jika kita ingin menambahkan gambar baru, maka kita bisa menambahkan kode :
    
    ![flex](https://user-images.githubusercontent.com/114371403/192683303-e3606629-1a93-44fc-a237-239d8f501eaf.png)
    Data baru yang kita inputkan tidak akan merusak tampilan yang telah kita buat, dengan penggunaan flex box maka data baru akan menyesuaikan dengan pembungkusnya (container).
    
    ![flex2](https://user-images.githubusercontent.com/114371403/192683311-ef40c7e2-bcd1-4482-acc9-f31efa2d9168.png)
---
## Algoritma dan Struktur Data
* ### Algoritma
    Algoritma adalah langkah atau metode yang direncanakan secara tersusun dan berurutan untuk menyelesaikan atau memecahkan masalah dengan sebuah instruksi atau kegiatan.
* ### Manfaat Algoritma
    Dengan implementasi algoritma, komputer dapat mengolah data, melakukan perhitungan, melakukan penalaran otomatis, dan menyelesaikan berbagai masalah yang ada di komputer.
* ### Sistem Algortima
    Di dalam algoritma, setidaknya memiliki beberapa hal berikut :
    * Input, setiap masalah harus dicarikan solusi agar dapat diselesaikan.
    * Output, artinya harus ada solusinya, bukan hanya dicari.
    * Proses, langkah-langkah yang dilakukan untuk menyelesaikan masalah.
    * Instruksi, perintah yang diberikan harus jelas untuk mengurangi kesalahan.
    * Tujuan akhir, yaitu algoritman berhasil menyelesaikan masalah.
* ### Pseudocode
    Pseudocode adalah bahasa sederahana yang menggambarkan bagaimana cara program berjalan. Pseudocode sendiri bersifat umum, karena ia tidak spesifik ke bahasa program tertentu.
* ### Penulisan
    * Penggunaan huruf kapital untuk kode perintah
    * 1 statement untuk 1 perintah
    * Buat dengan sederhana dan mudah dimengerti
    Contoh :
    
    ![nulis](https://user-images.githubusercontent.com/114371403/192683360-3514643f-bdb4-41f7-86fd-99a211ef0d41.png)
---
## JavaScript
* ### Pengenalan JavaScript
    Seperti bahasa pemrograman pada umumnya, JavaScript merupakan salah satu bahasa pemrograman yang tersedia. Tidak seperti HTML yang membutuhkan PHP untuk membuat fungsi lebih lanjut atau CSS yang perlu terhubung dengan HTML, Javascript dapat benar-benar berdiri sendiri dengan segala fitur yang ia punya.

* ### Variable
    Untuk mendeklarasikan variable, kita dapat membuat nya dengan seperti ini :
    
    ![variable](https://user-images.githubusercontent.com/114371403/192683397-8f32aed9-9e78-4db9-a766-a3ee3013fd59.png)
    Dari gambar di atas, terdapat 2 jenis variable dengan kata kunci yang berbeda,
    * "let" berarti variable tersebut dapat diubah.
    * "const" berarti variable tersebut tidak dapat diubah.
* ### Menampilkan Output
    Untuk menampilkan output kita dapat menggunakan sintaks console.log() :
    
    ![konsol](https://user-images.githubusercontent.com/114371403/192683343-35f4460d-a1a5-48ae-bf9a-e859210cceb1.png)
    Atau kita juga bisa menampilkan variable yang sudah memiliki datanya :
    
    ![konsolll](https://user-images.githubusercontent.com/114371403/192683349-7ca27c19-6d1f-48f0-ac51-d9abc5a4cc87.png)
    Maka outputnya :
    
    ![konsoll](https://user-images.githubusercontent.com/114371403/192683345-295ab9a1-f812-4102-b6e8-1f133e633052.png)
    
* ### Array
    Untuk menyimpan data yang banyak dalam satu variable, maka kita bisa menggunakan array.
    
    ![array](https://user-images.githubusercontent.com/114371403/192683267-bb963b43-0718-41bd-b77b-631577797490.png)
    Kemudian untuk mengaksesnya seperti ini :
    
    ![array2](https://user-images.githubusercontent.com/114371403/192683272-06348bf3-d20e-41dd-9932-6c42ffa70b08.png)
    Urutan dalam array dimulai dari 0.
* ### Operator
    Operator digunakan untuk menghitung suatu nilai. Ada beberapa operator di dalam JavaScript, antara lain :
    * ' + ' penjumlahan
    * ' - ' pengurangan
    * ' * ' perkalian
    * ' / ' pembagian
    * ' % ' modulus (menghasilkan sisa pembagian)
* ### Conditional
    Jika terdapat kondisi yang harus membuat syarat, maka kita dapat menggunakan if else.
    Contoh :
    
    ![ifelse](https://user-images.githubusercontent.com/114371403/192683318-f9c47dac-7704-4e7d-9ac6-8530cb6c9db7.png)
    Jika nilainya lebih dari 75 maka dia lulus, jika tidak maka tidak lulus.
* ### Loop
    Ketika kita ingin menampilkan sebuah data yang banyak, kita bisa menggunakan looping.
    
    ![loop](https://user-images.githubusercontent.com/114371403/192683354-2f5c568c-d84e-4c0c-ab6b-b57bcca1be62.png)
    Di atas kita memiliki variable 1 dengan angka 1, kemudian kita akan melakukan perulangan sama dengan kurang dari 5 kali. Selama kondisi tersebut bernilai True, maka data "i" akan terus di tambah hingga bernilai "false".
    
    ![loop2](https://user-images.githubusercontent.com/114371403/192683355-240325df-595f-4d4b-a67e-9679c2bb281f.png)
