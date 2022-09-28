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
    ![urutan markdwon](https://drive.google.com/file/d/12-tuwIv0ut3dGuTi9b9ppGUOAG9lnaDP/view?usp=sharing)

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
    ![git](git.png)
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
    ![kerangka](kerangka.png)

* ### Element
    Element di sebuah web dapat berupa teks, judul, gambar, video dan lain-lain.
    ![element](element.png)
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
    ![heading](heading.png)
    * paraghraf < p > untuk membuat kalimat
    ![paragraf](paragraf.png)
    * link < a > untuk mengarahkan ke suatu website
    ![link](link.png)
    * div < div > untuk memberi batasan
    * table < table > untuk membuat sebuah tabel
    ![tabel](tabel.png)
    * image < image > untuk menampilkan foto
    * video < video > untuk menampilkan video

* ### Form
    Di HTML kita bisa menginputkan sebuah data, nah data-data yang kita inputkan bisa dikelompokan di dalam tag < form >. 
    
    * Di tag < form > ini kita bisa menambahkan tag < input > untuk memasukkan data teks, seperti nama, alamat, nomor hp dan lain-lain.
    Ini sintaks nya :
    ![input2](input2.png)
    Output :
    ![input](input.png)

    * Kemudian ada tag < option > yang digunakan untuk memilih beberapa pilihan, biasa juga dibarengi dengan tag < select >.
    Ini sintaks nya :
    ![option2](option2.png)
    Output :
    ![option](option.png)

    * Kemudian ada tag < textarea > untuk menginput sebuah kalimat yang panjang.
    Ini sintaks nya :
    ![textarea2](textarea2.png)
    Output :
    ![textarea](textarea.png)

    * Kemudian ada tag < button > yang berfungsi sebagai tombol untuk mensubmit data atau form yang telah kita input sebelumnya.
    Ini sintaks nya :
    ![button2](button2.png)
    Output :
    ![button](button.png)

---
## CSS
* ### Pengertian CSS
    CSS atau kepanjangan dari Cascading Style Sheets adalah sebuah bahasa komputer yang digunakan untuk mendesain sebuah website.
* ### Penerapan  CSS
    CSS dapat diterapkan dengan berbagai cara, diantaranya :
    * Inline, yaitu langsung memasukkan CSS nya di dalam tag HTML.
    ![inline](inline.png)
    * Internal, sebuah element style yang kita buat di satu halaman atau file dengan HTML.
    ![internal](internal.png)
    * External, merupakan file CSS yang terpisah dengan HTML. Kita dapat menghubungkannya dengan menggunakan link.
    ![external](external.png)
* ### Penulisan CSS
    Penulisan CSS terdiri dari :
    ![penulisan](penulisan.png)
    * Selector, yaitu target yang ingin kita beri desain.
    * Properti, yaitu jenis desain yang ingin diterapkan.
    * Value, merupakan nilai yang dimasukkan dari properti, seperti warna, tinggi dan ukuran teks.
* ### Box Model
    Di dalam mendesain website, ada batasan di area tertentu yang harus di pahami, di antaranya :
    * Margin, yaitu area terluar.
    * Border, yaitu garis tepi.
    * Padding, yaitu area kosong.
    * Content, isi utama dari sebuah website. Seperti teks, foto, video dan lain-lain.
    ![box model](box_model.png)

* ### Kerja CSS
    Kode-kode atau sintaks dari CSS cukup beragam dan juga penerapannya akan langsung terlihat. Masing-masing dari setiap kode CSS yang dideklarasikan akan saling mempengaruhi satu sama lain.
    Contoh, kita memiliki 2 buah style, yang pertama inline :
    ![kerja2](kerja3.png)
    Kemudian yang kedua external :
    ![kerja3](kerja2.png)
    Jika keduanya digabungkan maka hasilnya :
    ![kerja](kerja.png)
    
* ### Flex Box
    Flex Box berguna untuk mengatur layout, posisi dan ukuran dari tiap elementnya. Dalam flex box terdapat istilah :
    * container, yang menjadi pembungkus dan mengatur tampilan dari element.
    * item, element yang ada di dalam container.
    Berikut adalah contoh codenya.
    ![felxx2](felxx2.png)
    Akan menampilkan :
    ![felxx](felxx.png)
    Kemudian jika kita ingin menambahkan gambar baru, maka kita bisa menambahkan kode :
    ![flex](flex.png)
    Data baru yang kita inputkan tidak akan merusak tampilan yang telah kita buat, dengan penggunaan flex box maka data baru akan menyesuaikan dengan pembungkusnya (container).
    ![flex2](flex2.png)
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
    ![nulis](nulis.png)
---
## JavaScript
* ### Pengenalan JavaScript
    Seperti bahasa pemrograman pada umumnya, JavaScript merupakan salah satu bahasa pemrograman yang tersedia. Tidak seperti HTML yang membutuhkan PHP untuk membuat fungsi lebih lanjut atau CSS yang perlu terhubung dengan HTML, Javascript dapat benar-benar berdiri sendiri dengan segala fitur yang ia punya.

* ### Variable
    Untuk mendeklarasikan variable, kita dapat membuat nya dengan seperti ini :
    ![variable](variable.png)
    Dari gambar di atas, terdapat 2 jenis variable dengan kata kunci yang berbeda,
    * "let" berarti variable tersebut dapat diubah.
    * "const" berarti variable tersebut tidak dapat diubah.
* ### Menampilkan Output
    Untuk menampilkan output kita dapat menggunakan sintaks console.log() :
    ![konsol](konsol.png)
    Atau kita juga bisa menampilkan variable yang sudah memiliki datanya :
    ![konsolll](konsolll.png)
    Maka outputnya :
    ![konsoll](konsoll.png)
* ### Array
    Untuk menyimpan data yang banyak dalam satu variable, maka kita bisa menggunakan array. 
    ![array](array.png)
    Kemudian untuk mengaksesnya seperti ini :
    ![array2](array2.png)
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
    ![ifelse](ifelse.png)
    Jika nilainya lebih dari 75 maka dia lulus, jika tidak maka tidak lulus.
* ### Loop
    Ketika kita ingin menampilkan sebuah data yang banyak, kita bisa menggunakan looping.
    ![loop](loop.png)
    Di atas kita memiliki variable 1 dengan angka 1, kemudian kita akan melakukan perulangan sama dengan kurang dari 5 kali. Selama kondisi tersebut bernilai True, maka data "i" akan terus di tambah hingga bernilai "false".
    ![loop2](loop2.png)
