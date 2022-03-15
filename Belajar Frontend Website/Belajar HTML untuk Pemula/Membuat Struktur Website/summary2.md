# Membuat Struktur Website

### Heading dan Paragraf

- Text Heading
Bagian-bagian penting yang berisi text dari file html yaitu untuk judul dan menerangkan hal penting. Text heading ada banyak
```html
<h1> Sekolah Koding </h1>
<h2> Sekolah Koding </h2>
<h3> Sekolah Koding </h3>
<h4> Sekolah Koding </h4>
<h5> Sekolah Koding </h5>
<h6> Sekolah Koding </h6>
```

- Text Paragraf
Isi dari heading dan text biasa penggunan 
```html
<p>content</p>
```

### Membuat Link
Untuk membuka halaman lain di HTML dengan menggunakan kode ```<a> </a>```. Tapi tidak cukup dengan **text a** nya saja, kita butuh dengan nama **attribute**
Attribute adalah **tambahan pada tag pembuka**. Jadi contohnya
```html
<a href="https://facebook.com">Link Facebook</a>
<a href="https://twitter.com" target=_newblank>Link Twitter</a>
```
1. Fungsi **herf** adalah untuk link yang ingin dituju akan tetapi user tidak akan melihat text herf itu sendiri. Untuk style bisa menggunakan CSS
2. Fungsi **target** adalah untuk mengarahkan **herf** untuk ditampilkan dalam new tab atau tab yang sama

### Menampilkan Gambar
Untuk menampilkan gambar dapat menggunakan elemen ```<img>``` tidak ada elemen penutupnya. Akan tetapi harus menggunakan beberapa attribut
1. Source adalah attribut untuk sumber gambar dengan menulis ```src="konten"``` konten dapat diisi tempat menyimpan gambar yang ini ditampilkan. 
Contoh : ```<img src="asset/logo.png">```
2. Alternatif adalah untuk mengganti source dengan tulisan/text untuk mewakili gambar yang di source dapat ditulis dengan ```alt="konten"```
Contoh : ```<img src="asset/logo.png" alt="gambar logo">```
3. Height dan widht untuk mengatur tinggi dan lebar gambar sesuai dengan selera kita dapat ditulis dengan ```height="isi tinggi" widht="isi lebar"``` angka dan format yang dipakai dapat disesuaikan dengan selera masing-masing

Contoh : 
```html
<img src="asset/logo.png" alt="gambar logo" height="100px" widht="100px">
```

### Penggunaan iframe
Iframe adalah elemen html agar dapat menampilkan halaman website tertentu dan dapat ditampilkan di web kita sendiri dapat menggunakan tag iframe

Dengan penulisannya yaitu ```<iframe></iframe>``` ada tag pembuka dan tag penutupnya
Akan tetapi harus menggunakan beberapa attribute yaitu:
1. Source dapat ditulis dengan ```src="isi web yang ingin ditampilkan"``` 
2. Mengatur lebar dan tinggi menggunakan ```height="isi tinggi"``` dan ```widht="isi lebar"```
3. Mengatur penggunaan frame border dapat ditulis dengan 
    - ```frameborder="0"``` yang artinya tanpa menggunakan border
    - ```frameborder="1"``` yang artinya menggunakan border

Contoh:
```html
<iframe src="https://www.petanikode.com/" height=500px widht=500px frameborder="0"></iframe>
```

### Formating Text
Formating text merupakan elemen di HTML untuk mengubah paragraph menjadi jenis text khusus
Elemen-elemen tersebut terdiri dari
| Elemen | Keterangan |
| ----- | ----- |
| ```<b>```  | Text tebal  |
| ```<strong>``` | Text penting  |
| ```<i>```  | Text miring  |
| ```<em>``` | Text yang ditekankan  |
| ```<small>```  | Text lebih kecil dari ```<p>```  |
| ```<del>``` | Text dicoret  |
| ```<ins>```  | Text digarisbawahi  |
| ```<sub>``` | Text subscript  |
| ```<sup>``` | Text superscript  |
Contoh:
```html
<p><b>Belajar</b>formating<em>text</em>di <strong>html</strong>dengan menggunakan<i>Visual Studio</i></p>
```

### Perbedaan Element Block dan Inline

**Block element** adalah element pada HTMl yang otomatis akan mengambil lebarnya selebar view port
**Inline element** adalah element pada HTML yang tetap 1 baris

1. Block Element contoh tagnya adalah ```<div></div>``` penggunaannya untuk membuat divisi atau bagian tertentu agar dapat memudahkan dalam melayout HTML dan otomatis membuat garis baru
2. Inline Element contoh tagnya adalah ```<span></span>``` mirip dengan div tapi perbedaannya adalah teks span tidak akan membuat jarak atau garis baru secara otomatis jika ingin membuat jarak atau garis baru maka ditambahkan tag ```<br>```

Contoh:
```html
<div>
    <p>Belajar html <span>dan <br> css</span> bagi pemula <br> untuk membangun website <br> dari nol</p>
</div>
```

### Doctype HTML
HTML punya banyak versi, versi terbaru HTML adalah HTML 5.

HTML harus melakukan deklarasi karena setiap versi HTML punya tag dan fitur berbeda-beda agar browser dapat membaca vesi HTML yang digunakan.

Untuk HTML 5 cukup dengan mengetik ```<!DOCTYPE html>``` diatas element ```<html>```. Sedangkan untuk versi lain bisa dilihat di browser kalian karena HTML dibawah versi 5 deklarasinya cukup ribet

