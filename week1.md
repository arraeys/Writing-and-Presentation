WRITING AND PRESENTATION TEST

# Unix Command Line dan Git

Biasanya kita mengakses *file* sistem dengan membuka aplikasi berbasis GUI yang dinamakan **File Explorer** jika kamu menggunakan sistem operasi Windows. Ternyata ada cara lain untuk mengakses *file* sistem tersebut yaitu dengan command-line interface (CLI), dengan CLI kita bisa mengakses file sistem hanya dengan mengetikkan perintah atau teks

## Apa itu CLI dan Shell

- Shell adalah program yang digunakan untuk berkomunikasi atau memerintah sistem
- CLI adalah jenis shell yang berbasis teks

## Penggunaan Git Bash

- Unduh Git Bash melalui tautan [berikut ini](https://git-scm.com/downloads)
- Kemudian instal di PC kamu

## Perintah untuk Git Bash

### Perintah Navigasi

- pwd, digunakan untuk melihat *current working directory*
- ls, digunakan untuk melihat daftar *file* yang ada di sebuah direktori
- cd <direktori>, digunakan untuk berpindah direktori

### Perintah Membuat *File* & Direktori

- touch, digunakan untuk membuat sebuah *file*
- mkdir, digunakan untuk membuat sebuah direktori

### Perintah Melihat Isi *File*

- head, digunakan untuk melihat beberapa *line* awal dari sebuah *file* teks
- tail, digunakan untuk melihat beberapa *line* akhir dari sebuah *file* teks
- cat, digunakan untuk melihat isi sebuah *file*

### Perintah Menyalin, Memindahkan, dan Menghapus File & Direktori

- cp, digunakan untuk menyalin *file* atau direktori
- mv, digunakan untuk memindahkan *file* atau direktori, bisa digunakan untuk *rename*
- rm, digunakan untuk menghapus file atau direktori

## Apa itu Git

- Git adalah perangkat lunak *open-source* yang digunakan sebagai *version control* (kontrol versi)
- Git dapat  melacak perubahan dalam sekumpulan *file* oleh karena itu Git banyak digunakan oleh *programmer* untuk berkolaborasi dalam mengembangkan perangkat lunak
- Git ditemukan pada 2005 oleh [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds)
- Dalam Git, kita akan mengenal repositori atau sering disingkat repo. Repo adalah sebuah folder yang bersisi *source code* (kode sumber)
- Terdapat 4 fundamental dalam Git Workflow
    - *Working Directory*
    - *Staging Area*
    - *Local Repository*
    - *Remote Repository*
- Jika melihat sebuah *file* dalam w*orking directory*, *file* tersebut bisa berada dalam tiga kemungkinan
    - File tersebut bisa di-*staged*, yang berarti *file* yang memiliki perubahan, ditandai untuk di-*commit* ke *local repository* (repositori lokal) tetapi belum di-*commit*.
    - File tersebut bisa dimodifikasi, yang berarti *file* memiliki perubahan belum disimpan di repositori lokal.
    - Filter di-*commit, y*ang berarti bahwa perubahan yang dibuat pada *file* tersebut disimpan dengan aman di *local repository* (repositori lokal).

## Perintah Pada Git

- git config, digunakan untuk mengatur nama penulis dan alamat email untuk digunakan dengan komit.
- git init, digunakan untuk memulai repositori baru.
- git add, digunakan untuk menambahkan file yang ada di *working directory* ke *staging area*
- git commit, digunakan untuk menambahkan semua file yang di-*staged* ke *local repository* (repositori lokal).
- git push, digunakan untuk menambahkan semua file yang di-*commit* di repositori lokal ke *remote repository*. Sehingga di *remote repository*, semua *file* dan perubahannya akan terlihat oleh siapa saja yang memiliki akses ke *remote repository* tersebut.
- git fetch, digunakan untuk mendapatkan *file* dari *remote repository* ke repositori lokal, tetapi tidak ke dalam *working directory*.
- git merge, digunakan menggabungkan *branch* lain ke dalam *branch* saat ini.
- git pull, digunakan untuk mendapatkan *file* dari *remote repository* langsung ke *working directory*
- git remote, digunakan untuk menghubungkan *local repository* (repositori lokal) dengan *remote repository*
- git status, digunakan untuk menampilkan semua *file* yang harus di-*commit*
- git log, digunakan melihat histori perubahan yang telah dilakukan, jadi semua *commit* akan tampil di sini

## Sekian dan Terima Kasih

# Hypertext Markup Language (HTML)

## Apa itu HTML

- Sederhananya, HTML adalah sebuah bahasa yang digunakan untuk membuat konten dan struktur dari halaman sebuah situs web
- Versi pertama HTML ditulis oleh [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) pada tahun 1993
- Versi terbaru HTML saat ini adalah HTML5. Versi ini merupakan versi yang direkomendasikan oleh World Wide Web Consortium (W3C)
- HTML5 pertama kali dirilis dalam ke publik pada tanggal 22 Januari 2008

## *Tools* yang harus dipersiapkan untuk membuat HTML

- Peramban Web (*Web Browser*), peramban web digunakan untuk menampilkan konten HTML
    - [Chrome](https://www.google.com/chrome/)
    - [Microsoft Edge](https://www.microsoft.com/en-us/edge)
    - [Firefox](https://www.mozilla.org/en-US/firefox/new/)
    - [Opera](https://www.opera.com/browsers/opera)
    - [Brave](https://brave.com/)
- *Text Editor*, text editor digunakan untuk menulis atau mengetikkan kode HTML
    - [Visual Studio Code](https://code.visualstudio.com/download), dikembangkan oleh Microsoft
    - [Sublime Text](https://www.sublimetext.com/)
    - [Atom](https://atom.io/), dikembangkan oleh GitHub
    - [Bracket](https://brackets.io/), dikembangkan oleh Adobe
    - [Notepad++](https://notepad-plus-plus.org/downloads/)

## Struktur HTML

```html
<!DOCTYPE html>
<html>
<head>
	<title>Judu Halaman/title>
</head>
<body>
	<h1>Judul Teks</h1>
	<p>Isi Paragraf</p>
</body>
</html>
```

- <!DOCTYPE html> menyatakan bahwa kode HTML yang dibuat menggunakan versi HTML5
- < html > menyatakan elemen akar dari halaman HTML
- < head > berisi informasi meta tentang halaman HTML
- < title > digunakan untuk membuat judul halaman HTML
- < body > menyatakan badan HTML, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, *hyperlink*, tabel, *list*, dan lain-lain.
- < h1 > digunakan membuat judul besar
- < p > digunakan untuk menyatakan paragraf

## Elemen HTML

Elemen HTML terdiri dari *tag* pembuka, kontennya, dan *tag* penutup.

```html
<tagname> Isi konten </tagname>
```

Contoh Elemen HTML

```html
<h1> Judul Besar </h1>
<p> Ini adalah paragraf </p>
```

## Atribut HTML

Atribut merupakan properti dari sebuah elemen HTML

```html
<tagname attribute="value"> Isi konten </tagname>
```

- Semua elemen HTML bisa memiliki atribut
- Atribut selalu diletakkan pada *tag* pembuka sebuah elemen
- Semua atribut yang bisa dipakai untuk elemen HTML bisa dilihat melalui [tautan](https://www.w3schools.com/tags/ref_attributes.asp) berikut ini

Contoh Atribut HTML

```html
<a href="google.com">Klik di sini untuk membuka Google </a>
```

## Komentar pada HTML

- Komentar adalah sebuah teks yang tidak akan tampil pada peramban web (*web browser*).
- Komentar digunakan untuk memberikan penjelasan lebih lengkap tentang kode HTML yang ditulis
    
    ```html
    <!-- Ketikkan komentar di sini -->
    ```
    
    > Perhatikan bahwa terdapat tanda seru (!) pada *tag* pembuka, tetapi tidak ada pada *tag* penutup.
    > 
    
    Contoh 
    
    ```html
    <!-- Ini adalah komentar. Komentar tidak akan tampil di peramban web (*web browser*) -->
    ```
    

## Ekstensi Live Server pada Visual Studio Code

- Setiap kita menuliskan kode HTML, kita harus me-*refresh* halaman web tersebut di peramban web (*web browser*) untuk menampilkan kode yang telah dibuat. Hal tersebut akan sangat merepotkan karena harus berulang kali me-*refresh* halamannya
- Solusi dari permasalahan tersebut adalah dengan menginstal ekstensi yang bernama **Live Server** pada Visual Studio Code
- Ekstensi Live Server memiliki fitur *live reload* yang memungkinkan kita untuk tidak berulang kali me-*refresh* halaman web

## *Tag* HTML Populer

- < p >, digunakan untuk membuat paragraf
- < h1 > - < h6 >, digunakan untuk membuat judul besar
- < i > atau < em >, digunakan untuk membuat teks miring
- < b > atau < strong >, digunakan untuk menebalkan teks
- < a >, digunakan untuk membuat *hyperlink*
- < hr >, digunakan untuk membuat garis pemisah horizontal
- < img >, digunakan untuk memanggil gambar
- < video >, digunakan untuk memanggil video
- < table >, digunakan untuk membuat tabel
- < form >, digunakan untuk membuat form

## Elemen Semantik pada HTML

- Elemen semantik adalah elemen yang memiliki arti.
- Terdapat beberapa *tag* semantik yang dapat digunakan untuk mendefinisikan bagian yang berbeda dari halaman web
    - < article >
    - < aside >
    - < details >
    - < figcaption >
    - < figure >
    - < footer >
    - < header >
    - < main >
    - < mark >
    - < nav >
    - < section >
    - < summary >
    - < time >
- Kegunaan menggunakan elemen semantik adalah meningkatkan aksesibilitas, meningkatkan SEO, serta lebih mudah di-*maintain*

## Deploy HTML

- Deploy adalah sebuah proses untuk menyebarkan atau mengunggah kode ke web server agak bisa di akses oleh banyak orang
- Kode HTML bisa disebarkan atau diunggah melalui layanan berikut
    - Netlify
    - GitHub Pages
    - Firebase
    - Microsoft Azure

## Sekian dan Terima kasih

# Cascading Style Sheet (CSS)

## Apa itu CSS?

- CSS adalah sebuah bahasa yang digunakan untuk mempercantik dan memberi gaya (*styling*) halaman HTML
- Dengan CSS, kita bisa mengubah warna, menggunakan *font custom*, mengedit format teks, mengatur tata letak, dan lainnya
- CSS pertama kali diperkenalkan pada tahun 1996

## Struktur CSS

```css
.selector{
  properti: nilai;
}
```

- *Selector* menunjuk ke elemen HTML apa yang ingin dipercantik atau diberi gaya
- Nama properti CSS dan nilai, dipisahkan dengan titik dua

## Komentar pada CSS

```css
/* Ini adalah komentar*/
p {
  font-size: 15px;
}
```

- Komentar CSS tidak ditampilkan di peramban web, tetapi dapat membantu memberi penjelasan mengenai kode CSS yang dibuat.

## Cara Memanggil file CSS ke dalam file HTML

### External CSS

- Dengan CSS eksternal, Kita bisa mengubah tampilan seluruh situs web hanya dengan mengubah satu *file*
- Setiap halaman HTML harus menyertakan referensi ke CSS eksternal di dalam elemen < link >, di dalam elemen < head >
- CSS eksternal dapat ditulis dalam *text editor* apa pun, dan harus disimpan dengan ekstensi .css
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<link rel="stylesheet" href="mystyle.css">
    	</head>
    	<body>
    		<h1>This is a heading</h1>
    		<p>This is a paragraph.</p>
    	</body>
    </html>
    ```
    

### **Internal CSS**

- CSS internal dapat digunakan jika satu halaman HTML tunggal memiliki gaya yang unik.
- CSS internal dibuat di dalam elemen < style >, di dalam elemen < head >
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<style>
    		body {
    		  background-color: linen;
    		}
    		
    		h1 {
    		  color: maroon;
    		  margin-left: 40px;
    		}
    		</style>
    	</head>
    	<body>
    	
    	<h1>KKN di Desa Penari/h1>
    	<p>KKN di Desa Penari adalah film horor dari Indonesia</p>
    	
    	</body>
    </html>
    ```
    

### Inline CSS

- CSS Inline dapat digunakan untuk memberikan gaya unik untuk satu elemen.
- Untuk menggunakan CSS Inline tambahkan atribut style ke elemen yang relevan. Atribut gaya dapat berisi properti CSS apa pun.
    
    ```html
    <!DOCTYPE html>
    <html>
    	<body>
    		<h1 style="color:blue;text-align:center;">Indonesia/h1>
    		<p style="color:red;">Indonesia adalah negara kepulauan/p>
    	</body>
    </html>
    ```
    

## Selector pada CSS

- Selector CSS digunakan untuk menemukan atau memilih elemen HTML yang ingin diberi gaya atau dipercantik.
- Selector CSS dapat dibagi ke dalam lima kategori:
    - Simple Selector (memilih elemen berdasarkan nama elemen, id, class)
    - Combinator Selector (memilih elemen berdasarkan hubungan spesifik antar elemen)
    - Pseudo-class Selector (memilih elemen berdasarkan keadaan tertentu)
    - Pseudo-elements Selector (memilih dan memberi gaya pada bagian dari sebuah elemen)
    - Attribute Selector (memilih elemen berdasarkan atribut atau nilai atribut)

### Selector berdasarkan nama elemen

```css
h1 {
  text-align: center;
  color: blue;
}
```

### Selector berdasarkan id

- Selector id menggunakan atribut id dari elemen HTML untuk memilih suatu elemen
- Id dari sebuah elemen adalah unik di dalam sebuah halaman, jadi selector id digunakan untuk memilih satu elemen yang unik
- Untuk memilih elemen dengan id tertentu, ketikkan karakter hash (#), diikuti dengan id elemen.
    
    ```css
    #judul_pertama{
     font-size:20px;
    	background-color:red;
    }
    ```
    

### Selector berdasarkan nama

- Selector class memilih elemen HTML dengan atribut class tertentu.
- Untuk memilih elemen dengan class tertentu, tulis karakter titik (.), diikuti dengan nama class.
    
    ```css
    .foto_profil{
      width:100px;
    }
    ```
    

### Universal Selector

Selector universal (*) memilih semua elemen HTML pada halaman.

```css
* {
 background-color : red;
}
```

### Chaining Selectors

Chaining selector dapat kita gunakan pada case/kasus berikut. Jika kita memiliki 3 tag elemen HTML pada CSS namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda

```css
h1 {
color : green;
}

h1.judul_pertama {
color : blue;
}
```

**Grouping Selector**

- Grouping selector memilih semua elemen HTML dengan *styling* yang sama.
- Untuk membuat grouping selector, pisahkan setiap selector dengan koma.
    
    ```css
    h1, h2, p {
      font-weight: bold;
      color: blue;
    }
    ```
    

## CSS !important

- !important CSS berada di level paling atas dari ID dan Class.
- Jika pada *styling* CSS kita menggunakan !important, maka *styling* sebelumnya baik itu id, nama elemen atau nama kelas akan di-*override*


# Algoritma

## Apa itu Algoritma?

- Algoritma adalah proses tersebut dilakukan dengan cara yang logis (masuk akal) dan sistematis (terurut)
- Berdasarkan Microsoft Press Computer and Internet Dictionary (1998), algoritma adalah urutan langkah logis tertentu untuk memecahkan suatu masalah
- Programming identik dengan memecahkan masalah sehingga pengetahuan tentang algoritma adalah hal yang harus
- Adapun ciri-ciri algoritma adalah sebagai berikut:
    - Memiliki input
    - Memiliki output
    - Definiteness (pasti)
    - Finiteness (ada batas)
    - Effectiveness (tepat dan efisien)
- Algoritma juga memiliki berbagai proses yaitu sebagai berikut:
    - Sequence, instruksi dijalankan secara berurutan
    - Selection, instruksi dijalankan jika memenuhi suatu kondisi
    - Iteration, instruksi berulang kali dijalankan selama memenuhi suatu kondisi
    - Concurrent, instruksi dijalankan secara bersamaan

## Penulisan Algoritma

Algoritma dapat disajikan dengan beberapa cara yaitu

### Deskriptif

Penulisan algoritma dengan cara deskriptif seperti kita menulis tutorial (tata cara)
dengan bahasa sehari-hari

### Flow Chart

Flow chart atau diagram alir, penyajian algoritmanya lebih mudah dibaca karena
memiliki tampilan visual. Flow chart menggunakan simbol bangun datar sebagai
representasi dari proses yang dilakukan

### Pseudo Code

Pseudo code adalah salah bentuk penulisan algoritma yang memiliki pendekatan terhadap sebuah bahasa pemrograman, namun pseudo code bukan bahasa pemrograman

Pada umumnya pseudocode memiliki 3 bagian:

- Judul : Penjelasan dari algoritma yang dibuat
- Deklarasi : Mendefinisikan/menyiapkan semua nama (variabel) yang akan
digunakan
- Deskripsi : langkah-langkah penyelesaian masalah

Tidak ada aturan baku dalam penulisan pseudocode, asalkan:

- Jelas
- Simple
- Konsisten
- Dan mudah dibaca orang lain

## Sekian dan Terima Kasih


# JavaScript Dasar

## Apa itu JavaScript

- JavaScript adalah bahasa pemrograman yang sangat powerful yang digunakan untuk logic pada sebuah website
- JavaScript juga dapat membuat website menjadi interaktif dan dinamis
- JavaScript berjalan di setiap peramban web (*web browser*) **karena setiap peramban web sudah memiliki JavaScript di dalamnya

## Console log pada JavaScript

Console log mencetak pesan ke web console. Pesan dapat berupa string, atau dapat berupa satu atau lebih objek JavaScript

```jsx
console.log("Hello world!");
```

## Komentar pada JavaScript

- Komentar adalah teks yang tidak akan dieksekusi oleh JavaScript. Komentar sangat berguna untuk memberikan penjelasan terkait kode JavaScript yang ditulis.
- Komentar pada JavaScript terdiri dari 2 yaitu single line dan multi-line
    
    ### Komentar Single Line
    
    - Komentar single line dimulai dengan //.
    - Teks apa pun antara // dan akhir baris akan diabaikan oleh JavaScript (tidak akan dieksekusi).
        
        ```jsx
        // Perintah untuk menampilkan teks Hello World ke konsol
        console.log("Hello world!");
        ```
        
    
    ### Komentar Multi-line
    
    - Komentar multi-line dimulai dengan /* dan diakhiri dengan */.
    - Teks apa pun di antara /* dan */ akan diabaikan oleh JavaScript.
        
        ```jsx
        /*
        Perintah di bawah ini
        untuk menampilkan teks Selamat Malam ke konsol
        */
        console.log("Selamat Malam")
        ```
        
    

## Tipe Data pada JavaScript

Ada 6 tipe data fundamental pada JavaScript

- Numbers
    - JavaScript hanya memiliki satu jenis angka.
    - Numbers bisa ditulis dengan, atau tanpa desimal
        
        ```jsx
        let phi= 3.14;     // Ditulis dengan desimal
        let diameter= 31;  // Ditulis tanpa desimal
        ```
        

- String
    - String adalah serangkaian karakter seperti "Hello World.
    - String ditulis dengan tanda kutip, bisa menggunakan tanda kutip tunggal atau ganda
        
        ```jsx
        let ucapan = "Selamat Malam";   // Menggunakan tanda kutip ganda
        let ucapan2 = 'Selamat Sore;   // Menggunakan tanda kutip tunggal
        ```
        

- Boolean
    - Boolean adalah jenis tipe data yang hanya memiliki 2 nilai yaitu true atau false
        
        ```jsx
        let benar = true;
        let salah = false;
        ```
        

- Null
    - Tipe data null adalah tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai
    - Null berbeda dengan string kosong. String kosong masih memiliki tipe data string
        
        ```jsx
        let ini_null = null;
        ```
        
    
- Undefined
    - Dalam JavaScript, variabel tanpa nilai, memiliki nilai undefined. Jenisnya juga tidak terdefinisi.
        
        ```jsx
        let halo;    // Nilainya tidak ada, jenisnya pasti undefined
        ```
        

- Object
    - Objek JavaScript ditulis dengan tanda kurung kurawal {}.
    - Properti objek ditulis sebagai pasangan nama:nilai, dipisahkan dengan koma.
        
        ```jsx
        const orang= {namaPertama:"Andrian", namaAkhir:"Ramadan", umur:19, jenisKelamin:"Laki-Laki"};
        ```
        

## Variabel pada JavaScript

- Variabel adalah tempat menampung data
- Terdapat 4 cara untuk membuat variabel
    - Menggunakan var
        
        ```jsx
        var x = 1;
        var y = 5;
        var z = x + y;
        ```
        
    - Menggunakan let
        
        ```jsx
        let nama = "Andrian Ramadan";
        ```
        
    - Menggunakan const
        
        ```jsx
        const phi = 3.14;
        ```
        
    
    ### Kapan menggunakan var?
    
    - var digunakan pada JavaScript dari tahun 1995 sampai 2015
    - let dan const ditambahkan ke JavaScript pada tahun 2015
    - Jika ingin kodenya berjalan di *browser* lama, harus menggunakan var.
    
    ### Kapan menggunakan let?
    
    - Penggunaan var sudah tidak direkomendasikan dan juga sudah lawas oleh karena itu para disarankan menggunakan let
    
    ### Kapan menggunakan const?
    
    - Jika ingin menampung nilai variabel yang tidak berubah atau konstan, seperti phi, kamu bisa gunakan const

## Jenis Operator pada JavaScript

- Ada berbagai jenis operator JavaScript:
    - Operator Aritmetika
    - Operator Penugasan
    - Operator Perbandingan
    - Operator Logika
    - Operator Kondisional
    - Operator Tipe

### Operator Aritmatika JavaScript

| Operator | Deskripsi |
| --- | --- |
| + | Penjumlahan |
| - | Pengurangan |
| * | Perkalian |
| ** | Eksponensiasi (ES2016) |
| / | Pembagian |
| % | Modulus (Sisa Bagi) |
| ++ | Increment |
| -- | Decrement |

### Operator Penugasan JavaScript

| Operator | Contoh | Sama Seperti |
| --- | --- | --- |
| = | x = y | x = y |
| += | x += y | x = x + y |
| -= | x -= y | x = x - y |
| *= | x *= y | x = x * y |
| /= | x /= y | x = x / y |
| %= | x %= y | x = x % y |
| **= | x **= y | x = x ** y |

### Operator Perbandingan JavaScript

| Operator | Deskripsi |
| --- | --- |
| == | sama dengan |
| === | nilai yang sama dan tipe yang sama |
| != | tidak sama |
| !== | tidak sama nilainya atau tidak sama jenisnya |
| > | lebih besar dari |
| < | kurang dari |
| >= | lebih besar dari atau sama dengan |
| <= | kurang dari atau sama dengan |
| ? | operator terner |

### Operator Perbandingan JavaScript

| Operator | Deskripsi |
| --- | --- |
| && | logika dan |
| || | logika or |
| ! | logika not |
|  |  |

### Operator Tipe JavaScript

| Operator | Deksripsi |
| --- | --- |
| typeof | Mengembalikan tipe variabel |
| instanceof | Mengembalikan nilai true jika sebuah objek adalah instance dari sebuah tipe objek |

## Kondisional

- Kondisional merupakan statement percabangan yang menggambarkan suatu kondisi
- Statement kondisional akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut
- Dalam JavaScript ada beberapa statement kondisional yaitu sebagai berikut:
    - if, untuk menentukan blok kode JavaScript yang akan dieksekusi jika suatu kondisi benar.
        
        ```jsx
        if (umur > 18) {
          console.log("Memasukan kedewasaan");
        }
        ```
        
    - else, untuk menentukan blok kode yang akan dieksekusi, jika kondisi yang sama salah
        
        ```jsx
        if (umur > 18) {
          console.log("Memasuki fase kedewasaan");
        }else
        {
        	console.log("Memasuki fase anak-anak");
        }
        ```
        
    - else if, untuk menentukan kondisi baru untuk diuji, jika kondisi pertama salah
        
        ```jsx
        if (umur > 18) {
          console.log("Memasuki fase kedewasaan");
        }else if(umur > 50){
        	console.log("Memasuki fase lansia");
        }else
        {
        	console.log("Memasuki fase anak-anak");
        }
        ```
        
    - switch, untuk menentukan banyak blok kode alternatif yang akan dieksekusi
        
        ```jsx
        let nilai = "A"
        switch(expression) {
          case "A":
            console.log("Sangat Baik")
            break;
          case "B":
            console.log("Baik")
            break;
        	case "C":
        	  console.log("Cukup")
        	  break;
        	case "D":
        		 console.log("Buruk")
        		 break;
          default:
            console.log("Tidak ada")
        }
        ```
        

## Perulangan (Looping)

- Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
- Ada beberapa cara untuk melakukan looping
    - FOR LOOP
        
        ```jsx
        // Kode dibawah ini akan menampilkan angka 1 - 5
        for (let i = 1; i <= 5; i++) {
          console.log(i)
        }
        ```
        
    - WHILE LOOP
        
        ```jsx
        // Kode dibawah ini akan menampilkan angka 1 - 10
        let i = 1;
        while (i <= 10) {
         console.log(i)
          i++;
        }
        ```
        
    - DO WHILE
        
        ```jsx
        // Kode dibawah ini akan menampilkan angka 1 - 10
        let i = 1;
        do {
        console.log(i)
          i++;
        }
        while (i <= 10);
        ```
        
    

## Sekian dan Terima Kasih
