# Mengenal lebih banyak element

### Membuat Komentar
Komentar dapat digunakan sebagai alat pembantu untuk ngasih informasi untuk bagian-bagian tertentu kepada kita agar kita tidak bingung dalam membuat layout pada HTML.
Selain itu membantu dalam membuat website bersama dengan tim agar tidak adanya misscom.
Penulisan komentar dapat dituliskan dengan ```<!-- isi Komentar -->``` atau dengan menggunakan shortcut ctrl + / (di Visual Studi Code) sehingga tidak usah ditulis secara manual
Contoh:
```html
<!-- Heading -->
    <h1> Belajar HTML </h1>
    <h2> Belajar HTML </h2>
    <h3> Belajar HTML </h3>
    <h4> Belajar HTML </h4>
    <h5> Belajar HTML </h5>
    <h6> Belajar HTML </h6>
<!-- Akhir Heading -->
```

### Membuat lebih dari 1 halaman HTML dan menghubungkannya
Kita harus membuat file dengan format html selain index.html disini saya beri contoh misal about-me.html
Bisa diisi file tersebut dengan source code berikut
```html
<!DOCTYPE html>
<html>
    <head> 
        <title>About Me</title>
    </head>
    <body>
        <!-- Heading -->
        <h3> About Me </h3>
        
        <!-- Isi Konten -->
        <h4>Hallo Semua!!</h4>
        <p>Nama asli author adalah Hilal Akbar yang berasal dari Bandung Jawa Barat dan sedang berkuliah</p>
    </body>
</html>
```

Untuk mengakses file HTML yang baru di **index.html** dapat di tambahkan source code berikut
```html
<a href="about-me.html" target="_blank">About Me</a>
```
- Fungsi tag a yaitu untuk memanggil file HTML yang baru dan ingin di tampilkan
- Fungsi attribut href yaitu untuk mengetahui file mana yang ingin dipanggil berserta letak file tersebut apakah di dalam subfolder atau terletak di folder yang sama
- Fungsi attribut targat yaitu untuk menjelaskan apakah ditab yang sama atau new tab

Peletakan source code diatas dapat disesuaikan dengan keperluan kalian. Misal
```html
<!DOCTYPE html>
<html>
    <head> 
        <title>Belajar HTML</title>
    </head>
    <body>
        <!-- Menu Website -->
        <div>
            <a href="index.html">Home</a>
            <a href="about-me.html">About Me</a>
        </div>

        <!-- Heading -->
            <h1> Belajar HTML </h1>
    
        <!-- Isi Website -->
        <div>
            <p>Belajar html dan css bagi pemula untuk membangun website dari nol</p>
        </div>
    </body>
</html>
```
