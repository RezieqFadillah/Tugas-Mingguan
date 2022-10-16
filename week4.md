## API

API adalah singkatan dari Application Programming Interface. API sendiri merupakan interface yang dapat menghubungkan satu aplikasi dengan aplikasi lainnya. API menyediakan sebuah data yang dapat diambil dan digunakan oleh kita.

* ### Mengambil data dari API dengan async  await fetch

    Untuk mengambil data dari API, kita membutuhkan sebuah link API yang memang sudah menyediakan source yang kita butuhkan.

    ![re](re.png)

    Kemudian setelah kita dapatkan link API nya, kita buat function dengan memiliki variabel response untuk mengakses link API. Kemudian json() untuk membuka link nya.

    ![re2](re2.png)

* ### Menampilkan data dari API

    Data yang kita ambil dari API tidak akan langsung bisa ditampilkan ke browser HTML, tetapi hanya akan masuk ke console JavaScript. Untuk itu kita gunakan DOM. Caranya adalah dengan memasukkan code HTML di dalam JavaScript. Cara nya adalah dengan DOM innerHTML.

    ![re3](re3.png)

    Setelah itu maka tampilan browser akan mengikuti dari code HTML yang diinput JavaScript, namun di sini kita telah menambahkan element CSS.

    ![re4](re4.png)

## Responsive

Untuk dapat membuat website yang kita buat mengikuti ukuran dari layar yang dipakai, maka kita perlu membuat website yang responsive.

Cara membuat website yang responsive kita perlu mendefinisikan "viewport" di dalam tag meta, dan juga menyesuaikan scalenya.

![re41](re41.png)

* ### max-width

    Jika kita menginputkan gambar, maka ukuran gambar tersebut akan langsung tampil dengan ukuran bawaannya (default). 

    ![re5](re5.png)

    Di atas bisa kita lihat gambarnya ditampilkan hingga melewati ukuran layar browser. Untuk itu kita perlu memberikan properti "max_width" pada gambar.

    ![re6](re6.png)

    ![re7](re7.png)

    Nilai 60% di atas adalah ukuran 60% dari gambarnya, dan jika kita buka dari ukuran layar lain seperti hp, maka gambar nya akan tetap ditampilkan 60% dari ukuran layar hp.

* ### media-query

    Jika kita ingin suatu element juga berubah bentuk mengikuti layar, maka kita dapat menggunakan "media-query".

    ![re8](re8.png)

    ![re82](re82.png)

    ![re81](re81.png)

    Di atas kita memiliki sebuah tombol, jika kita mengecilkan ukuran browser maka posisinya akan tetap. Namun jika kita ingin mengubahnya maka kita terapkan media-query.

    ![re9](re9.png)

    Penerapan properti display bernilai "flex" artinya memungkinkan layar yang fleksibel, dan juga properti flex-direction merujuk pada element yang dituju berupa "column" (kolom).

    ![re91](re91.png)

## Bootstrap

Bootstrap merupakan sebuah framerok yang berbasis HMTL, CSS dan JavaScript yang dapat digunakan untuk membuat website menjadi lebih mudah. Fitur-fitur yang tersedia dalam bootstrap sangat membantu kita dalam membuat website, dan yang paling terlihat sangat menggunakan bootstrap adalah tampilannya.

* ### Penerapan

    Untuk menggunakan bootstrap pertama-tama kita perlu memanggil link bootstrap yang akan kita gunakan.

    ![re10](re10.png)

    Kunci utama dari penggunaan bootstrap adalah pada penerapannya di class. Class yang ada kita buat untuk memanggil class yang sudah disediakan oleh bootstrap. Class yang kita panggil sudah terdapat source code, jadi kita tidak perlu membuat source code lagi.

    Contoh, kita di sini membuat nav murni HTML.

    ![re11](re11.png)

    ![re12](re12.png)

    Kita bisa saja menambahkan element CSS, namun akan sangat lama untuk membuatnya, nah disini lah kita gunakan bootstrap. Dengan memanggil class yang memang tersedia di bootstrap, maka jika kita panggil maka tampilannya akan menyesuaikan dengan element classnya.

    ![re13](re13.png)

    Maka tampilannya akan berubah sesuai dengan element bootstrap yang dipanggil.

    ![re14](re14.png)