---
layout: post
title: "Sass dan SCSS"
---
<!-- ### Penjelasan Sass dan SCSS -->

### Penjelasan Sass dan SCSS

Sass (Syntactically Awesome Stylesheets) adalah preprocessor CSS yang membantu menulis kode CSS dengan lebih efisien, terstruktur, dan mudah dipelihara. Sass memungkinkan penggunaan fitur seperti variabel, nesting, mixin, dan lainnya—yang tidak tersedia di CSS biasa.

SCSS (Sassy CSS) adalah salah satu dari dua sintaks yang digunakan di Sass, dan bentuknya sangat mirip dengan CSS konvensional. Sintaks SCSS lebih umum digunakan karena kompatibel dengan file .css.

---

#### Perbedaan Sass dan SCSS

- *Sass (Indentation syntax)*  
  Tidak menggunakan tanda kurung kurawal {} dan titik koma ;, lebih mirip bahasa pemrograman Python.  
  Ekstensi file: .sass

- *SCSS (Sassy CSS)*  
  Menggunakan tanda kurung kurawal dan titik koma seperti CSS biasa.  
  Ekstensi file: .scss

---

#### Fungsi Utama Sass/SCSS

- *Menggunakan Variabel*  
   Dapat menyimpan nilai seperti warna, font, ukuran ke dalam variabel.

- *Nesting (Penulisan Bersarang)*  
   Menulis selector di dalam selector lain seperti struktur HTML.

- *Partials dan Import*  
   Memecah file menjadi bagian-bagian kecil, lalu digabung kembali saat dikompilasi.

- *Mixin dan Function*  
   Menyimpan blok kode yang bisa digunakan ulang dengan parameter.

- *Inheritance (Pewarisan)*  
   Menggunakan @extend untuk mewarisi properti dari selector lain.

- *Operasi Matematika dan Logika*  
   Mendukung perhitungan langsung di dalam CSS (misalnya width: 100% / 3;).

![Sass dan SCSS](/assets/images/sass-dan-scss.jpg)