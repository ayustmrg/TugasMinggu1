# CSS  
CSS adalah Bahasa yang digunakan untuk mendesain halaman website.  
Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnnya.  

Struktur CSS :  

<img src="css.1.jpeg" width="200" height="100">  

Merupakan selector. Selector maksudnya adalah bagian mana yang mau distyling.  

Agar lebih muda memahami code antar sesame programmer dapat menggunakan CSS Comment. Kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan. Comment ini pasti sealalu ada dalam Bahasa pemrograman apapun.  

Contoh comment :  

<img src="css2.jpeg" width="200" height="100">  

</br>

**Cara menggunakan CSS**
* Inline style  
adalah kita menambahkan CSS pada atribut element HTML  

<img src="css3.jpeg" width="200" height="100">  

* Internal  
Menggunakan element <br style > di dalam elemen <br head >  

<img src="css4.jpeg" width="200" height="100">  

* External  
Menggunakan elemen <br link > di dalam elemen <br head >  

<img src="css5.jpeg" width="200" height="100">

</br>

**Tag Name**  
Kita bisa menggunakan Tag Elemen HTML secara kangsung pada CSS. JIka menggunakan tag Element, maka ini bersifat global. Global artinya akan mempengaruhi seluruh Tag Elemen HTML yanga da pada file tersebut.  
Contoh penggunaan :  
Kita akan mengubah <br h1 > pada code berikut :  

<img src="css6.jpeg" width="200" height="100">  

Jika kita memasukkan code CSS  

<img src="css7.jpeg" width="200" height="100">  

Maka akan menghasilkan :  

<img src="css8.jpeg" width="200" height="100">  

</br>

**CSS Class Name**  
Kita bisa menggunakan atribut clss pada elemen HTML lalu memanggil nama class tersebut. HTML yang memiliki class yang sama, akan mempunyai styling yang sama saat digunakan pada CSS.  
Contoh code yang memiliki class yang sama :  

<img src="css9.jpeg" width="200" height="100">  

Style css dengan memanggil class dari attribute elemen tag HTML  

<img src="css10.jpeg" width="200" height="100">  

Maka akan menghasilkan tampilan :  

<img src="css11.jpeg" width="200" height="100">  

Walapun ketiga heading memiliki element tag yang sama, tidak membuat styling/desain yang sama untuk ketiga heading karena menggunakan class.  
> Gunakan (.) saat memanggil clss pada CSS  

</br>

**CSS Multiple Clss**  
Kita dapat menggunakan lebih dari 1 clss yang berbeda untuk 1 elemen HTML.  
Semisal kita memiliki 2 heading. Kita ingin memiliki warna yang sama. Tapi, kita ingin format heading yang satu huruf besar (uppercase) dan heading yang huruf kecil (lowercase).  
Pada file html :  

<img src="css12.jpeg" width="200" height="100">  

Pada file CSS :  

<img src="css13.jpeg" width="200" height="100">  

Maka akan menghasilkan :  

<img src="css14.jpeg" width="200" height="100">  

</br>

**CSS-ID Name**  
ID Name bersifat unik artinya hanya ada 1 nama ID ada 1 element HTML. Biasanya digunakan jika hanya ada 1 element pada 1 page.  
Contohnya : navigator header dan footer  
> Gunakan (#namaID) saat memanggil element ID HTML pada CSS  
Contoh file HTML dengan ID attribute pada section navigation :  

<img src="css15.jpeg" width="200" height="100">  

Pada style css nya :  

<img src="css16.jpeg" width="200" height="100">  

 Maka akan menghasilkan :

 <img src="css17.jpeg" width="200" height="100">  

 Perbedaan Class Name dengan ID Name :
 * Gunakan ID Name jika hanya ada 1 elemen pada file/halaman HTML.
 Contohnya navigation dan footer
 * Gunakan Class Name jika aka nada beberapa element HTML yang memiliki styling/desain yang sama.
 Contohnya : 
-	Kita ingin Heading Blog kita memiliki desaun yang sama
-	Kita ingin setiap link memiliki styling/desain yang sama  

</br>

**Nasted Element**  
Konsep CSS sama dengan HTML yaitu setiap element memiliki parent dan child.  
Pada HTML :  

<img src="css18.jpeg" width="200" height="100">  

Pada CSS :

<img src="css19.jpeg" width="200" height="100">  

Maka akan menghasilkan :

<img src="css20.jpeg" width="200" height="100">  

</br>

**!important CSS**  
!important CSS berada di level paling atas dari ID dan Class.  
Maksudnyanya adalah jika pada styling CSS kita menggunakan !important, maka styling sebelumnya baik itu ID Name atau Class Name akan di override.  
Contoh pada file HTML :  

<img src="css21.jpeg" width="200" height="100">  

Pada file CSS :

<img src="css22.jpeg" width="200" height="100">  

Maka akan menghasilkan :  

<img src="css23.jpeg" width="200" height="100">  

</br>

Note book :  

<img src="css24.jpeg" width="200" height="100">  

> Margin adalah itu jarak keluar box model  

> Padding adalah  jarak di dalam kotak  

> Block adalah menguasai satu layer  

> Inline : menguasai konten aja  

> Statis : posisi secara default  

> Statis itu ditempatkan sesuai dengan nulis element  

> Statis : berarti dia memiliki wilayahnya sendiri  

> Relative bisa dipindahin  

> Posisi absolut akan mengikuti posisi induknya yang relative  

> z-index gunanya untuk mengatur posisi  

> Posisi absolute akan selalu mengikuti relative  

> Jikalau hendak  membuat tulisan dan gambar sebelah belahan memakai display: flex  

> flexbox istilahnya (terminalogi kalau pengen menggunakan flex display)  

> Repository : tempat kia menyimpan kerjaa.progress  

> Local : kerjaan/ progress yang masih ada di device  

> Push : mengirim kerjaan/progress ke github repository



