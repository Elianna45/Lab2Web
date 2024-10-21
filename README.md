# Lab2Web
### langkah 1 membuat dokumen html

##Deklarasi HTML
- <!DOCTYPE html>: Menandakan bahwa ini adalah dokumen HTML5.
##Bagian <head>
- <meta charset="UTF-8">`**: Mengatur pengkodean karakter ke UTF-8.
- <meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Membuat tampilan responsif di perangkat seluler.
- <title>CSS Dasar</title>`: Menetapkan judul halaman sebagai "CSS Dasar".
##Bagian <body>
- Header: <h1>CSS Internal dan <i>Inline CSS</i></h1> menampilkan judul dengan teks miring.
- Navigasi (<nav>): Tiga tautan untuk menuju halaman "CSS Dasar", "CSS Eksternal", dan "HTML Dasar".
- ID Selector (#intro): <div id="intro"> digunakan untuk mengatur gaya khusus
- Class Selector (.button .btn-primary): Tombol bertuliskan "Informasi selengkapnya" dengan gaya yang ditetapkan melalui kelas CSS.
<hr
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Dasar</title>
    </head>
    <body>
      <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
      </header>
      <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
      </nav>
      <div id="intro">
        <h1>Hello World</h1>
        <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
        <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
      </div>
    </body>
    </html>


![image](https://github.com/user-attachments/assets/9df61883-7fb5-46c6-a8db-b4141cd172e3)








### langkah 2 Mendeklarasikan CSS Internal
#<style>: Menyertakan CSS internal yang mengatur gaya elemen pada halaman.
#body: Menentukan font untuk seluruh halaman dengan menggunakan 'Open Sans', dan memilih jenis sans-serif sebagai alternatif.
#header: Mengatur tinggi minimum elemen header menjadi 80px dan menambahkan border di bagian bawah dengan warna #77CCEF.
#h1: Mengatur ukuran font menjadi 24px, memberikan warna teks biru (#0F189F).
#h1 i: Mengubah warna teks miring di dalam elemen <h1> menjadi abu-abu (#6d6a6b).
    
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Dasar</title>
    </head>
    <body>
      <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
      </header>
      <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
      </nav>
      <div id="intro">
        <h1>Hello World</h1>
        <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
        <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
      </div>
    </body>
    </html>
    <head>
        <title>CSS Dasar</title>
        <style>
          body {
            font-family: 'Open Sans', sans-serif;
          }
          header {
            min-height: 80px;
            border-bottom: 1px solid #77CCEF;
          }
          h1 {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
          }
          h1 i {
            color: #6d6a6b;
          }
        </style>
      </head>
  
![image](https://github.com/user-attachments/assets/83922492-594f-4deb-9771-0e0a2e7fdfbe)






### langkah 3 Menambahkan Inline CSS
#text-align: center;: Mengatur teks dalam paragraf agar terletak di tengah.
#color: #ccd8e4;: Mengatur warna teks menjadi abu-abu muda (#ccd8e4).
<br>

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Dasar</title>
    </head>
    <body>
      <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
      </header>
      <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
      </nav>
      <div id="intro">
        <h1>Hello World</h1>
        <p style="text-align: center; color: #ccd8e4;">
         Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
        <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
      </div>
    </body>
    </html>
    <head>
        <title>CSS Dasar</title>
        <style>
          body {
            font-family: 'Open Sans', sans-serif;
          }
          header {
            min-height: 80px;
            border-bottom: 1px solid #77CCEF;
          }
          h1 {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
          }
          h1 i {
            color: #6d6a6b;
          }
        </style>
      </head>
      
![image](https://github.com/user-attachments/assets/a88ab162-3308-4111-bdca-dab1085819bd)


### langkah 4 Membuat CSS Eksternal
#background: #20A759;: Menetapkan warna latar belakang hijau.
#color: #fff;: Mengatur warna teks menjadi putih.
#padding: 10px;: Memberikan ruang di dalam elemen navigasi.
#nav a: Mengatur gaya untuk semua tautan (<a>) di dalam elemen navigasi.
#color: #fff;: Menetapkan warna teks tautan menjadi putih.
#text-decoration: none;: Menghilangkan garis bawah pada tautan.
#padding: 10px 20px;: Memberikan ruang di sekitar teks tautan (10px vertikal, 20px horizontal).

    <!DOCTYPE html>
    <html lang="id">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CSS Internal dan Inline CSS</title>
        <style>
            h1 {
                color: blue;
                font-family: Arial, sans-serif;
            }
            i {
                color: gray;
            }
            nav {
                background: #20A759;
                padding: 10px;
            }
            nav a {
                color: white;
                text-decoration: none;
                padding: 10px 20px;
                font-family: Arial, sans-serif;
            }
            nav a:hover {
                background-color: #1a864d;
            }
            h2 {
                color: blue;
                font-family: Arial, sans-serif;
                text-align: center;
            }
            p {
                color: gray;
                text-align: center;
                font-family: 'Arial', sans-serif;
            }
            a.info {
                color: blue;
                text-decoration: none;
            }
            a.info:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <h1 style="text-align: center;">CSS Internal dan <i>Inline CSS</i></h1>
        <nav>
            <a href="#">CSS Dasar</a>
            <a href="#">CSS Eksternal</a>
            <a href="#">HTML Dasar</a>
        </nav>
        <h2>Hello World</h2>
        <p>
            Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <strong>Pemrograman Web</strong> di <em>Universitas Pelita Bangsa</em>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>
        <p style="text-align: center;">
            <a href="#" class="info">Informasi selengkapnya.</a>
        </p>
    </body>
    </html>

  
![image](https://github.com/user-attachments/assets/24a80140-9648-4fef-9ba6-0ae406b43a1b)

### langkah 5 Menambahkan CSS Selector dan semua style yang ada pada style_ekstenal.css
#ID selector Mengatur gaya pada elemen HTML dengan atribut id, yang bersifat unik.
#selector mengatur gaya pada satu atau lebih elemen HTML dengan atribut class, yang dapat digunakan berkali-kali.

    <!DOCTYPE html>
    <html lang="id">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Dasar</title>
      <style>
        body {
          font-family: 'Open Sans', sans-serif;
        }
        header {
          min-height: 80px;
          border-bottom: 1px solid #77CCEF;
          text-align: center;
        }
        h1 {
          font-size: 24px;
          color: #0F189F;
          text-align: center;
          padding: 20px 10px;
        }
        h1 i {
          color: #6d6a6b;
        }
        nav {
          background-color: #20A759;
          padding: 10px;
        }
        nav a {
          color: #fff;
          text-decoration: none;
          padding: 10px 20px;
          font-size: 16px;
        }
        nav a:hover {
          background-color: #1a864d;
        }
        #intro {
          margin: 20px auto;
          background-color: #4a9fbb;
          padding: 20px;
          color: #fff;
          border-radius: 8px;
        }
        #intro h1 {
          color: white;
        }
        #intro p {
          color: #ccd8e4;
          max-width: 2000px;
          text-align: center;
        }
        .button.btn-primary {
          color: white;
          background-color: #f44336;
          padding: 10px 20px;
          text-decoration: none;
          border-radius: 5px;
          display: inline-block;
          margin-top: 20px;
        }
        .button.btn-primary:hover {
          background-color: #d32f2f;
        }
      </style>
    </head>
    <body>
      <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
      </header>
      <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
      </nav>
      <div id="intro">
        <h2>Hello World</h2>
        <p>
          Kami sedang belajar HTML dan CSS dasar, pada mata kuliah 
          <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
          Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
      </div>
    </body>
    </html>

![image](https://github.com/user-attachments/assets/1e81aa6d-0627-42f7-aaa7-42e1d68aadd6)
