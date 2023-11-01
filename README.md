# Lab6Web
Nama : Anggita Risqi Nur Clarita

NIM : 312210450

Kelas : TI.22.A.4

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Modul Praktikum 6|[Click Here](https://drive.google.com/file/d/1rTE4CJPmYSEkku9gYS2hreq2crAibMTD/view)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Twitter Bootstrap|[Click Here](#twitter-bootstrap)|

## Praktikum
> ### Instruksi Praktikum
> 1. Persiapkan text editor misalnya **VSCode**.
>
> 2. Buat folder baru dengan nama **lab6_css_framework**.
>
> 3. Buat file baru dokumen html.
>
> 4. Buat struktur dasar dari dokumen HTML.
>
> 5. Buatlah layout web sederhana menggunakan css frameword ([Twitter Bootstrap](https://getbootstrap.com/)).

## Twitter Bootstrap
1. ### Membuat file baru dokumen html

    ```html
    <!doctype html>
    <html lang="en">
        <head>
            <!--Required Meta Tags-->
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            
            <!--Bootstrap CSS-->
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
            <title>Layout Sederhana</title>
        </head>
        <body>
            <!--Bootstrap Bundle with Popper-->
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
        </body>
    </html>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/1.png)
    **Keterangan** : Buat document html, sertakan tag `<meta name="viewport">`, CSS dan JS Bootstrap. Tempatkan tag `<link>` di `<head>` untuk CSS kita, dan tag `<script>` untuk bundel JavaScript kita sebelum penutup `<body>`.


2. ### Container
    ```html
    <!doctype html>
    <html lang="en">
        <head>
            <!--Required Meta Tags-->
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width, initial-scale=1">
            
            <!--Bootstrap CSS-->
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
            <title>Layout Sederhana</title>
        </head>
        <body>
            <!--Container Start-->
            <div class="container shadow-lg">
                <!--Heading Start-->
                <div class="card-body bg-light p-3">
                    <h1 class="text-secondary py-3 text-opacity-50 fw-bold">Layout Sederhana</h1>
                </div>
                <!--Heading End-->
            </div>
            <!--Container End-->

            <!--Bootstrap Bundle with Popper-->
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
        </body>
    </html>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/2.png)
    **Keterangan** : Script HTML tersebut digunakan untuk membungkus atau sebagai wadah yang menampung elemen-elemen lain, seperti teks, gambar, tabel dan sebagainya.


3. ### Navbar
    ```html
    <!--Navbar Start-->
    <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: #1f5faa;">
        <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav">
                <li class="nav-item active ms-4">
                    <a class="nav-link text-light fs-5 fw-semibold" aria-current="page" href="Lab6Web.html">Home</a>
                </li>
                <li class="nav-item ms-4">
                    <a class="nav-link fs-5 fw-semibold" href="#">Article</a>
                </li>
                <li class="nav-item ms-4">
                    <a class="nav-link fs-5 fw-semibold" href="#">About</a>
                </li>
                <li class="nav-item ms-4">
                    <a class="nav-link fs-5 fw-semibold" href="#">Contact</a>
                </li>
                </ul>
            </div>
        </div>
    </nav>
    <!--Navbar End-->
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/3.png)
    **Keterangan** : Script HTML tersebut digunakan untuk bagian navigasi, navigasi navbar dibuat berdasarkan opsi `.nav`.  Navigasi di navbar juga akan berkembang untuk menempati ruang horizontal sebanyak mungkin agar konten navbar tetap sejajar.
   

4. ### Jumbotron
    ```html
    <!--Jumbotron Start-->
    <div class="jumbotron p-2 text-secondary bg-opacity-25" style="background-color:#e4e4e5;">
        <h1 class="p-3 text-secondary fw-bold">Hello World!</h1>
        <p class="lead p-3 text-secondary">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        <a href="#" class="btn btn-primary mb-3 fw-semibold mx-3">Learn more &raquo;</a></p>
    </div>
    <!--Jumbotron End-->
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/4.png)
    **Keterangan** : Script HTML tersebut digunakan untuk menampilkan informasi yang di-highlight pada sebuah halaman website. Penggunaan jumbotron bertujuan agar pengunjung bisa lebih fokus dan menaruh perhatian lebih pada pesan yang ditampilkan.


5. ### Row dan Box
    ```html
    <!--Row Start-->
    <div class="row">
        <!--Box Start-->
        <div class="col-md-9">
            <div class="row">
                <div class="col-3 mx-4">
                    <div class="col mt-4">
                        <div class="card pt-3" style="border: 0;">
                            <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle" alt="...">
                            <div class="card-body">
                                <h5 class="card-title text-center">Heading</h5>
                                <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-2">View Detail</a></p>
                            </div>
                        </div>
                    </div>
                </div>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/5.png)


    ```html
    <!--Row Start-->
    <div class="row">
        <!--Box Start-->
        <div class="col-md-9">
            <div class="row">
                <div class="col-3 mx-4">
                    <div class="col mt-4">
                        <div class="card pt-3" style="border: 0;">
                            <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle" alt="...">
                            <div class="card-body">
                                <h5 class="card-title text-center">Heading</h5>
                                <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-2">View Detail</a></p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3 mx-4">
                    <div class="col mt-4">
                        <div class="card pt-3" style="border: 0;">
                            <img src="https://dummyimage.com/120/3e73e6/fff.png" class="card-img-top rounded-circle" alt="...">
                            <div class="card-body">
                                <h5 class="card-title text-center">Heading</h5>
                                <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-2">View Detail</a></p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3 mx-4">
                    <div class="col mt-4">
                        <div class="card pt-3" style="border: 0;">
                            <img src="https://dummyimage.com/120/71e6d4/fff.png" class="card-img-top rounded-circle" alt="...">
                            <div class="card-body">
                                <h5 class="card-title text-center">Heading</h5>
                                <p class="card-text text-center">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                                <p class="card-text text-center"><a href="#" class="btn btn-secondary mt-2">View Detail</a></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--Box End-->
    </div>
    <!--Row End-->
    ```

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/6.png)
    **Keterangan** :  Row digunakan untuk mengatur elemen-elemen di dalam grid. Box digunakan untuk mengelompokkan dan mengatur konten dalam sebuah halaman website.


6. ### Widget
    ```html
    <!--Widget Start-->
    <div class="col-md-3">
        <div class="my-3 mt-5">
            <div class="list-group" style="border-radius: 0;">
                <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold;">Widget Header</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
            </div>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/7.png)


    ```html
    <!--Widget Start-->
    <div class="col-md-3">
        <div class="my-3 mt-5">
            <div class="list-group" style="border-radius: 0;">
                <a href="#" class="list-group-item list-group-item-action active" aria-current="true" style="font-weight: bold;">Widget Header</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
            </div>
            <div class="list-group my-4" style="border-radius: 0; border: 1px">
                <a href="#" class="list-group-item list-group-item-action active " aria-current="true" style="font-weight: bold;">Widget Text</a>
                <a href="#" class="list-group-item list-group-item-action">
                    <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                </a>
            </div>
        </div>
    </div>
    <!--Widget End-->
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/8.png)
    **Keterangan** : Widget digunakan untuk menampilkan berbagai fungsionalitas pada halaman web.


7. ### Divider
    ```html
    <!--Divider Start-->
    <div>
        <!--Section 1-->
        <div class="mb-5" style="width: 900px; border: 0;">
            <h2>First featurette heading.</h2>
            <div class="row no-gutters">
                <div class="col-md-3">
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" class="card-img-top rounded-square" style="width: 200px;" alt="...">
                </div>
                <div class="col-md-8">
                    <div class="card-body">
                        <p class="card-text lead p-3 fs-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
            </div>
        </div>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/9.png)


    ```html
    <!--Divider Start-->
    <div>
        <!--Section 1-->
        <div class="mb-5" style="width: 900px; border: 0;">
            <h2>First featurette heading.</h2>
            <div class="row no-gutters">
                <div class="col-md-3">
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" class="card-img-top rounded-square" style="width: 200px;" alt="...">
                </div>
                <div class="col-md-8">
                    <div class="card-body">
                        <p class="card-text lead p-3 fs-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
            </div>
        </div>
        <!--Section 2-->
        <div class="mt-5 mb-5" style="width: 900px; border: 0;">
            <h2>First featurette heading.</h2>
            <div class="row">
                <div class="col-md-8">
                    <div class="card-body">
                        <p class="lead p-3 fs-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" class="card-img-top rounded-square" style="width: 200px;" alt="...">
                </div>
            </div>
        </div>
    </div>
    <!--Divider End-->
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/10.png)
    **Keterangan** : Divider digunakan untuk membuat garis pemisah antara elemen-elemen di dalam sebuah halaman website dan pada halaman ini devider digunakan untuk memisahkan antar section.


8. ### Footer
    ```html
    <!--Footer Start-->
    <div class="card-footer text-start bg-dark text-light p-2">
        <p>&copy; 2021 - Universitas Pelita Bangsa</p>
    </div>
    <!--Footer End-->
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/11.png)
    **Keterangan** : Footer terletak di bagian bawah halaman website. Footer biasanya berisi informasi penting tentang website, seperti: Informasi hak cipta, seperti tahun pembuatan dan nama pemilik website.


## Tampilan Website Secara Keseluruhan 

![image](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/screenshot/home.png)

Script lengkapnya bisa langsung liat di sini : [Lab6Web.html](https://github.com/AnggitaRisqiNC/Lab6Web/blob/main/lab6_css_framework/Lab6Web.html)

## Finish