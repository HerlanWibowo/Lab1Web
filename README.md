# Pemrograman Web 1 Praktikum-1
## Jawaban Pertanyaan
1. tidak ada error saat dijalankan tapi tidak muncul
2. tag p untuk membuat paragaraf sedangkan br untuk brake line memindahkan teks kebawah
3. tag title untuk memberikan judul pada gambar sedangkan alt untuk memberikan keterangan gambar jika gambar tidak bisa ditampilkan
4. Sebaiknya kedua atribut tersebut di isi agar dapat meyesuaikan pada halaman website
5. _blank =untuk membuka dokumen pada tab baru, _self =untuk membuka dokumen di tab yag sama, _top=untuk membuka dokumen di semua jendela, _parent=untuk membuka dokumen dalam bingkai induk
    
## Praktikum 1
-Buka Visual Studio Code dan Browser
![VS Code](/image%20src/VS%20Code.png)
Agar mempercepat saya gunakan template html dengan menekan (!) dan tab pada keyboard

-Buka file tersebut pada web browser
![Browser](/image%20src/Browser.png)

-Saya menambahkan teks paragraf di bawah ini pada halaman web <br>

        <!-- ini adalah paragraf pertama -->
        <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
        Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
        HTML.</p>
         <!-- ini adalah paragraf pertama -->
        <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
        mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
![Paragraf 1](/image%20src/paragraf%201.png)

-Saya akan membuat paragraf pertama jadi rata ke tengah dan paragraf kedua jadi rata ke kanan

        <!-- Ini adalah paragraf pertama -->
        <p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
        Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
        yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
        tag-tag dasar HTML.</p>
        <!-- Ini adalah paragraf kedua -->
        <p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
        kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
        dengan menggunakan tag dasar html.</p>
![Paragraf 2](/image%20src/paragraf%202.png)

-Menambahkan 2 judul untuk kedua paragraf 
        
        <!-- judul paragraf pertama -->
        <h1>Belajar Dasar HTML</h1>
        <!-- judul paragraf kedua -->
        <h2>Paragraf pada HTML</h2>
![Paragraf 3](/image%20src/paragraf%203.png)

-Memformat paragraf pertama dengan menambahkan :

        tag <mark> = untuk menandakan teks
        tag <bold> = untuk menebalkan teks
        tag <em> = untuk memiringkan teks
        tag <u> = untuk menggarisbawahi teks
![Paragraf 4](/image%20src/paragraf%204.png)

-Menambahkan gambar pada paragraf ketiga

        <h3>Menambahkan Gambar</h3>
        <img src="https://www.pelitabangsa.ac.id/wp-content/uploads/2019/09/LOGO_UPB_NEW-1.png" width="200px" title="Logo Universitas UPB"/>
![Logo](/image%20src/nambah%20gambar.png)

-Menambahkan Hyperlink

        <nav>
        <a href="lab-1 tag dasar.html">Dasar HTML</a>
        <a href="lab-1 halaman 2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
        </nav>
![Hyperlink](/image%20src/nambah%20hyperlink.png)
        
