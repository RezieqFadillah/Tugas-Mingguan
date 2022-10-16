## API

API adalah singkatan dari Application Programming Interface. API sendiri merupakan interface yang dapat menghubungkan satu aplikasi dengan aplikasi lainnya. API menyediakan sebuah data yang dapat diambil dan digunakan oleh kita.

* ### Mengambil data dari API dengan async  await fetch

    Untuk mengambil data dari API, kita membutuhkan sebuah link API yang memang sudah menyediakan source yang kita butuhkan.

    ![re1](https://user-images.githubusercontent.com/114371403/196013951-9f14cf13-6020-48bd-abcc-1143dbc147e1.png)

    Kemudian setelah kita dapatkan link API nya, kita buat function dengan memiliki variabel response untuk mengakses link API. Kemudian json() untuk membuka link nya.

    ![re2](https://user-images.githubusercontent.com/114371403/196013953-1d7185e5-c13b-4643-9761-9b3c1d4e0a62.png)

* ### Menampilkan data dari API

    Data yang kita ambil dari API tidak akan langsung bisa ditampilkan ke browser HTML, tetapi hanya akan masuk ke console JavaScript. Untuk itu kita gunakan DOM. Caranya adalah dengan memasukkan code HTML di dalam JavaScript. Cara nya adalah dengan DOM innerHTML.

    ![re3](https://user-images.githubusercontent.com/114371403/196013955-11229d35-5d9d-49cd-a583-ef6dd7a366d0.png)

    Setelah itu maka tampilan browser akan mengikuti dari code HTML yang diinput JavaScript, namun di sini kita telah menambahkan element CSS.

    ![re31](https://user-images.githubusercontent.com/114371403/196013958-a60a1240-2f68-4ac8-b7f3-0d9683c87426.png)

## Responsive

Untuk dapat membuat website yang kita buat mengikuti ukuran dari layar yang dipakai, maka kita perlu membuat website yang responsive.

Cara membuat website yang responsive kita perlu mendefinisikan "viewport" di dalam tag meta, dan juga menyesuaikan scalenya.

![re41](https://user-images.githubusercontent.com/114371403/196013778-da5497e8-65ca-4460-9386-c4fd253634aa.png)

* ### max-width

    Jika kita menginputkan gambar, maka ukuran gambar tersebut akan langsung tampil dengan ukuran bawaannya (default). 

    ![re5](https://user-images.githubusercontent.com/114371403/196013765-c9afe485-64c6-4e65-8d97-76161a984dd2.png)

    Di atas bisa kita lihat gambarnya ditampilkan hingga melewati ukuran layar browser. Untuk itu kita perlu memberikan properti "max_width" pada gambar.

    ![re6](https://user-images.githubusercontent.com/114371403/196013767-ca500bdb-17fb-4e44-bcca-4007492b1b62.png)

    ![re7](https://user-images.githubusercontent.com/114371403/196013768-c9f146b0-9f5a-469b-9209-63166846dd0a.png)

    Nilai 60% di atas adalah ukuran 60% dari gambarnya, dan jika kita buka dari ukuran layar lain seperti hp, maka gambar nya akan tetap ditampilkan 60% dari ukuran layar hp.

* ### media-query

    Jika kita ingin suatu element juga berubah bentuk mengikuti layar, maka kita dapat menggunakan "media-query".

    ![re8](https://user-images.githubusercontent.com/114371403/196013769-e374ca27-a185-4267-8a6b-e1bcc39f2491.png)

    ![re82](https://user-images.githubusercontent.com/114371403/196013781-03603478-1520-47a6-b8c8-dc3c1c9d420d.png)

    ![re81](https://user-images.githubusercontent.com/114371403/196013779-8b79ad36-1d7e-44eb-9155-17cf6bfe291f.png)

    Di atas kita memiliki sebuah tombol, jika kita mengecilkan ukuran browser maka posisinya akan tetap. Namun jika kita ingin mengubahnya maka kita terapkan media-query.

    ![re9](https://user-images.githubusercontent.com/114371403/196013770-99f3ea9e-4f0b-49e0-8e5f-5f03180adf04.png)

    Penerapan properti display bernilai "flex" artinya memungkinkan layar yang fleksibel, dan juga properti flex-direction merujuk pada element yang dituju berupa "column" (kolom).

    ![re91](https://user-images.githubusercontent.com/114371403/196013782-f5597202-06d1-48a6-afc2-5b40bbb77641.png)

## Bootstrap

Bootstrap merupakan sebuah framerok yang berbasis HMTL, CSS dan JavaScript yang dapat digunakan untuk membuat website menjadi lebih mudah. Fitur-fitur yang tersedia dalam bootstrap sangat membantu kita dalam membuat website, dan yang paling terlihat sangat menggunakan bootstrap adalah tampilannya.

* ### Penerapan

    Untuk menggunakan bootstrap pertama-tama kita perlu memanggil link bootstrap yang akan kita gunakan.

    ![re10](https://user-images.githubusercontent.com/114371403/196013771-b5603f4d-97be-40e7-a4f3-124cbaf15716.png)

    Kunci utama dari penggunaan bootstrap adalah pada penerapannya di class. Class yang ada kita buat untuk memanggil class yang sudah disediakan oleh bootstrap. Class yang kita panggil sudah terdapat source code, jadi kita tidak perlu membuat source code lagi.

    Contoh, kita di sini membuat nav murni HTML.

    ![re11](https://user-images.githubusercontent.com/114371403/196013773-d6c0d476-782a-4840-8a5d-699e6bc94477.png)

    ![re12](https://user-images.githubusercontent.com/114371403/196013774-fb499f55-a3f9-4434-8f08-6b7958ac58bc.png)

    Kita bisa saja menambahkan element CSS, namun akan sangat lama untuk membuatnya, nah disini lah kita gunakan bootstrap. Dengan memanggil class yang memang tersedia di bootstrap, maka jika kita panggil maka tampilannya akan menyesuaikan dengan element classnya.

    ![re13](https://user-images.githubusercontent.com/114371403/196013776-e9ffe6ad-e0df-42fd-afad-108fdf872f3e.png)

    Maka tampilannya akan berubah sesuai dengan element bootstrap yang dipanggil.

    ![re14](https://user-images.githubusercontent.com/114371403/196013777-a39ad27c-e05e-4042-a981-69de63b5c934.png)
