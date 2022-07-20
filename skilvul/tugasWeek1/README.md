# Git

<h2> Apa itu Git?</h2>
<i> merupakan Vertion Control System, sistem yang merekam perubahan yang ada di projek dari waktu ke waktu</i>

<h2>Tahap bekerja dengan Git :</h2>
<p>1. Working Directory,<i> yaitu membuat perubahan pada file yang ada dalam direktory</i><br>
2. Staging, <i>yaitu tahap menyiapkan perubahan yang akan di simpan.</i><br>
3. Commit, <i>menyimpan draf perubahan file yang sudah di buat. Seperti mencatat tanggal pembuatan commit, siapa yang yang membuat commit, dan lain-lain.</i> </p>
<hr>
<h2> Cara menggunakan Git :</h2>
<p>1. kita bisa mendownload terlebidahulu<br><a href="https://git-scm.com/download/win">clik disini untuk mendownload</a> Download for windows<br></p>
2. konfigurasi Git<br>

```git
git config --global user.name "nama_anda"

git config --global user.email "email_anda"
```

<br>
3. membuat git repository dengan menggunakan

```git
git init
```

<br>
4. kemudian kita akan membuat file dengan menggunakan

```git
touch nama_file
```

<br>
5. Untuk melihat perubahan apa saja yang sudah terjadi, kita dapat menggunakan:

```git
git status
```

<br>
6. kemudian kita akan menambahkan file ke dlaam stagging area, dengan menggunakan command

```git
git add nama_file
```

dengan di ikuti oleh nama file yang ingin dimasukan ke dalam stagging area

<br>
7. selanjutnya, untuk membuat sebuah commit kita dapat menggunakan command

```git
git commit -m "pesan deskriptif"
```

<br>
8. kemudian untuk melihat history perubahan pada project, kita dapat menggunakan command

```git
git log
```

<br>
9. kita bisa memastikan isi dari directory saat ini dengan menggunakan commad:

```git
ls -la
```

<hr>

<h2>Git Brance</h2>
<i>fitur branch biasanya digunakan ketika ingin membuat versi yang tidak ingin menggunakan branch utama</i>
<br>

<p> untuk membuat branch yang baru kita dapat menggunakan command</p>

```git
git branch nama_branch
```

<p>untuk berpindah branch kita dapat menggunakan command:</p>

```git
git checkout nama_branch
```

<br>

<p>untuk memastikan kita telah berpindah branch, kita dapat menggunakan :</p>

```git
git branch
```

nah, sekarang tanda (\*) sudah berpindah ke nama_branch.

<hr>
<h2>Git remote</h2 >
<p>untuk menambahkan remote ke dalam repository kita, kita bisa menambahkan command:</p>

```git
git remote add origin <link dari remote repository>
```

<br>
<p>untuk memastikan remote tersebut sudah berhasil di tambahkan, kita bisa menggunakan command:</p>

```
git remote
```

<br>

<p>untuk mengupload perubahannya, kita bisa menggunakan:</p>

```
git push
```

<br>
<p> biasanya pada percobaan pertama, akan mendapatkan error, dikarenakan remote repository tidak memiliki branch master. </p>
<p>oleh karena itu kita bisa push branch ini sekaligus set remote sebagai upstream, dengan menggunakan command:</p>

```
git push --set-upstream origin maaster
```

<br>
<hr>

<h1 style="color: lightgreen"> HTML (Hyper Text Markup Language)</h1>

<p>HTML adalah singkatan dari <b>Hyper Text Markup Language</b>.</p>

<p>HTML adalah bahasa komputer yang digunakan untuk membuat kerangka atau struktur untuk Web pages (halaman website) di internet.</p>

## HTML Tag

<p>Pada umumnya HTML memiliki 2 type tag: </p>
<li>Opening tag</li>
<li>Closing tag
<img src="https://th.bing.com/th/id/R.8e18f8d34e11a6c7e10c784ed530cf1f?rik=twF56lFmVAmQtQ&riu=http%3a%2f%2fgirldevelopit.github.io%2fgdi-featured-html-css-intro%2fimg%2ftagbreakdown.png&ehk=xo%2b8NQGyRZrDdSs0ZSebQMZNB3%2fIwy4reYONWA3stzc%3d&risl=&pid=ImgRaw&r=0" style="width: 25%">
<br/>
<hr>

## HTML Element

<p>Ada dua jenis HTML Element, yaitu:</p>

<p><li>HTML Element yang memiliki Opening Tag (tag pembuka) dan Closing Tag (tag penutup)</li></p>

<p><li>Empty HTML Element: memiliki Self-closing Tag, yang hanya memiliki Opening Tag (tag pembuka) dengan garis miring sebelum kurung tutup </li></p>

<p>contoh <img src="https://th.bing.com/th/id/R.bb7f3314b84ad22a36fe012426a3b54d?rik=Yf4eoYP0MMAXpg&riu=http%3a%2f%2fwww.webdevelopersnotes.com%2fwp-content%2fuploads%2fhtml-course-the-br-break-tag.png&ehk=uAe%2fM6bfhWiolC719ebXFQOCZw6AOi3Q2sfUPBKRVTU%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" style="width:15%" /></p>

<hr>

## HTML Attribute

<p>contohnya pada tag img berikut:<br/><img src="https://th.bing.com/th/id/R.2e5401eea6ffb00fc777c942f5cbfd66?rik=p7mpsZOiT6AehA&riu=http%3a%2f%2fweb.simmons.edu%2f%7egrabiner%2fcomm244%2fweekone%2fhtml-attributes.jpg&ehk=7peIl%2bSNWnzzcNR0Cp4qC%2fduTFu7%2bckpgt433DPOaFs%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" style ="width:60%">

<li><i style="color: lightblue">src</i> yang berfungsi untuk menentukan sumber gambar, dan diberikan value (nilai) untuk diarahkan ke tautan</li>
<li><i style="color: lightblue">alt</i> yang berfungsi sebagai keterangan tentang gambar ketika gagal di loading </li>

<hr>

## HTML Comment

<p>HTML comment digunakan untuk memberi <b>catatan kecil yang menjelaskan kode yang kita tulis.</b> </p>

```comment
<!--  this commet -->
```

<br/>

## HTML untuk menampilkan teks

<ul><li> Heading</li></ul>
<p><img src="https://1.bp.blogspot.com/-Srnw_8jBHSY/XvHQqaCppZI/AAAAAAAAOuU/cikYtvXLix8dNc-qFMG4j50e-94FCpzLgCLcBGAsYHQ/s1600/heading%2B1%2Bto%2B6.jpg" style = "width:20%" />

<ul><li> Paragraph</li></ul>
<p>Untuk membuat paragraf pada halaman website, maka dibutuhkan tag</p>

```html
<p>.....</p>
```

<ul><li> Link /Anchor</li></ul>
<p>Untuk membuat link pada halaman web, maka diperlukan tag

```html
<a href="">..... </a>
```

Tag memiliki attribute <i style = "color:lightblue">href</i> yang berguna untuk menyimpan link website yang dituju.

<ul><li> Huruf tebal</li></ul>
<p> tag yang digunakan biasanya

`<b>`
atau
`<strong>`
untuk membuat tulisan menjadi tebal.</p>

<ul><li> Huruf miring</li></ul>
<p>

`<i>` dan `<em>`
Untuk membuat huruf bercetak miring pada HTML.

<hr>

## HTML Multimedia

<ul><li>Gambar</li></ul>
<p>Untuk menampilkan gambar pada halaman sebuah website, maka kita membutuhkan tag</p>

```
<img src="..." alt="...">
```

<ul><li>Video</li></ul>
<p>untuk menampilkan gambar kita bisa menulis tag:</p>

```
<video width=""  height="">
  <source src ="bisa_diisi_link_ke_videonya" type="video/tipe-videonya" />
</video>
```

<ul><li>Audio</li></ul>
<p> mirip dengan video, untuk menampilkan audio dalam HTML dapat menggunakan:</p>

```
<audio controls>
   <source src = "link_audio" type = " type_audio" />
</audio>
```

<hr>

## HTML untuk table

<p>Untuk membuat sebuah tabel di HTML cukup membutuhkan tiga tag, yaitu:

`<table>` sebagai element utama.
`<tr>` atau dikenal sebagai table row tag, digunakan untuk membuat baris baru di dalam `<table>`.
`<td>` atau dikenal sebagai table data tag, digunakan sebagai container (wadah) dari data yang kita mau isi di dalam `<tr>`.
Kita juga bisa menggunakan tag `<th>` sebagai pengganti `<td>` untuk membuat header cell (biasanya digunakan untuk menampilkan judul kolom).</p>

<p><img src="https://i0.wp.com/i.ytimg.com/vi/u58vfl571n4/maxresdefault.jpg?resize=618%2C348&ssl=1" width="25%"/></p>

<hr>

## Layout Website

<p>Layout suatu website biasanya terdiri dari:

<li>Header</li>
<li>Navigation bar</li>
<li>Main Content</li>
<li>Footer</li>
</p>
<p>Semantic element menjelaskan tujuan dari element tersebut kepada browser dan pemrogram lain yang membaca kodenya. Semantic element tidak mempengaruhi tampilan dari halaman web, karena itu adalah fungsi dari CSS.</p>

<p>Berikut adalah beberapa contoh dari semantic element:

`<section>` menandakan bagian dalam sebuah halaman web.<br/>
`<header>` merupakan bagian tajuk dari sebuah halaman web.<br/>
`<footer>` merupakan bagian halaman web yang terletak di bagian bawah konten utama.<br/>
`<article>` menandakan sebuah blok teks yang isinya independen terhadap element lain dalam halaman web.<br/>
`<nav>`adalah bagian yang berisi tautan navigasi utama. Kalian mungkin sering melihat menu navigasi yang berisi tautan ke halaman "Beranda", "Kontak kami", "Galeri", dan lain-lain.<br/>
`<aside>` adalah bagian di samping konten utama. Kontennya sebaiknya berhubungan dengan element di sebelahnya.</p>

<hr>

<h1 style = "color: purple"> CSS (Cascading Style Sheets) </h1>

<h2 style = "color: lightgreen"> Pengartian CSS </h2>

<p>CSS adalah singkatan dari Cascading Style Sheets. <br/>CSS adalah bahasa komputer yang digunakan untuk menambahkan design ke suatu halaman website di internet.</p>

<p>Ada 3 cara untuk menyisipkan CSS ke dalam HTML, yaitu:

1. Inline CSS, yaitu menggunakan attribute style untuk menyisipkan kode CSS langsung di dalam HTML element.

2. Internal CSS, yaitu menggunakan element `<style>` untuk menyisipkan kode CSS. Element `<style>` tersebut diletakkan di dalam element .

3. External CSS, yaitu sebuah file CSS terpisah yang disambungkan dengan file HTML dengan menggunakan element `<link>`.</p>

<p>CSS syntax terdiri dari selector, property, dan value.</p>

```
selctor {
    properti: value;
}
```

<h2 style = "color: lightgreen"> Box model CSS </h2>

<p>Box model terdiri dari:

<b style="color: lightblue">margin</b> yaitu area terluar yang kosong setelah border. Margin bersifat transparan.<br>
<b style="color: lightblue">border</b> yaitu garis tepi yang membungkus padding dan konten.<br/>
<b style="color: lightblue">padding</b> yaitu area kosong di antara konten dan border. Padding bersifat transparan.<br/>
<b style="color: lightblue">content</b> yaitu konten (value/nilai) dari HTML element. Bisa berupa teks, gambar, video, ataupun suara.</p>
<img src="https://th.bing.com/th/id/R.7fe34aa2fbace874bf0baa7ada960a22?rik=PZekKXadMIknfw&riu=http%3a%2f%2fictacademy.com.ng%2fwp-content%2fuploads%2f2017%2f10%2fbox-model.png&ehk=13fBgEc%2bOrZmlRLVwy6muMCW7SNGLpXw%2fwYMMcHgg1A%3d&risl=&pid=ImgRaw&r=0" width=25% />

<hr>

<h2 style = "color: lightgreen"> CSS Display</h2>

<h2 style ="color: lightgreen">display: none vs visibility: hidden</h2>
<p>Kalau kita menggunakan properti  <i style="color:lightblue">display : none</i>  tampilan dari element di sekitarnya juga ikut berubah. Karena Saat kita menggunakan properti itu, halaman web kita akan ditampilkan seolah-olah element tersebut tidak ada.</p>

<p>Saat kita memberi nilai <i style="color:lightblue">hidden</i> pada properti <i style="color:lightblue">visibility</i> si gambar, ia akan tidak ditampilkan, namun ruang yang tadinya ia tempati tetap akan ada di situ.

<h2 style = "color: lightgreen"> Position : static </h2>

<p>seluruh properti <i style="color:lightblue">position</i> dari HTML element memiliki nilai static. Element dengan properti tersebut tidak akan terpengaruh oleh properti top, bottom, left, dan right.</p>

<h2 style = "color: lightgreen"> position: relative </h2>

<p><i style="color:lightblue">posisi relative</i> akan diposisikan relatif dari posisi normalnya. Kita bisa memberikan properti top, right, bottom, dan left pada element dengan posisi relative. Element lain di sekitar element dengan posisi relative tidak akan disesuaikan dengan ruang yang ditinggalkan oleh element.</p>

<h2 style = "color: lightgreen"> position: fixed </h2>

<p>Element dengan <i style ="color: lightblue">posisi fixed</i> akan diposisikan relatif terhadap viewport browser, di mana akan selalu berada di tempat yang sama jika walaupun halaman website di-scroll.</p>
<p>Kita bisa memberikan properti top, bottom, right, dan left pada element yang memiliki style position: fixed. Posisinya relatif pada viewport browser, jadi kalau diberi properti left:0px maka ia akan terus berada di bagian kiri jendela browser.</p>

<hr>

<h2 style = "color: lightgreen"> Mengatur Viewport</h2>

<p>Viewport adalah daerah yang menampilkan halaman web yang sedang kita akses.
Ukuran viewport tidak selalu sama dengan resolusi layar perangkat.
</p>Untuk membuat halaman website menjadi responsif, maka kita perlu menambahkan

`meta` data berikut ini di dalam element
`<head>` di file HTML.</p>

```
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

<p>di mana meta data tersebut akan memberikan instruksi kepada browser untuk mengatur bagaimana dimensi dan skala dari halaman website kita.</p>
<p>Penjelasan kode di atas:

<li> <mark>width=device-width </mark> memberitahu browser untuk mengikuti lebar layar dari perangkatnya. Sebab lebar layar tiap perangkat berbeda-beda.</li>
<li><mark>initial-scale=1.0 </mark>memberitahu browser tingkat pembesaran (zoom level) dari halaman itu.</li></p>

<hr>

<h1 style = "color: yellow">Algoritma </h1>

<p>Untuk dapat menggunakan semua bahasa programming, yang perlu kita pelajari dan pahami adalah Algoritma!</p>

<h2>Pseudocode</h2> 
<p>adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.</p>
<img src="https://1.bp.blogspot.com/-sX69iHQjkO0/WGHiOfytBEI/AAAAAAAADEY/Vf9Fg3b4AFsx9PQD1XXi2zAo_4cD5-S5wCEw/s1600/contoh-pseucode.JPG" width = "50%">
