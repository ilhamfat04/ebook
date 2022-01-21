---
sidebar_position: 3
---

# 3. Persiapan yang dilakukan

Beberapa hal yang harus kita persiapkan untuk mengerjakan study case diatas adalah terkait hal teknis seperti instalasi text editor dan non teknis seperti pengenalan tag - tag pada HTML.

## 3.1 Instalasi Code Editor

**Code editor** merupakan sebuah perangkat lunak penyunting teks yang dirancang khusus untuk menyunting teks yang berkaitan dengan kode program komputer oleh pemrogram. Code editor memiliki beberapa keunggulan dalam menuliskan kode editor dibandingkan dengan text editor, yakni adanya highlighting, code snippets, autocompletion, error detection, dll.
Code editor yang akan digunakan adalah Visual Studio Code atau yang biasa dikenal VSCode, VSCode dipilih karena memiliki keunggulan seperti cross platform, code debugging, source control, integrated terminal. Berikut adalah cara instalasi VSCode:

1. Download VSCode

   Download terlebih dahulu file installer VSCode melalui situs resminya [code.visualstudio.com](https://code.visualstudio.com/)

2. Proses Instalasi

   - Double klik pada file installer nya atau klik kanan kemudian pilih Run as Administrator.
   - Jika muncul peringatan **Run as Administrator**, silahkan klik **Yes**.
   - Pilih “I accept the agreement” untuk menyetujui “License Agreement”, kemudian klik **Next**.
   - Untuk Select Destination Location bisa di biarkan saja jika lokasi instalasi tidak akan diubah. Klik **Next**
   - Klik **Next** lagi jika tidak akan merubah Start Menu Folder
   - Di bagian Select Additional Tasks centang semua. Kemudian **Next**
   - Lalu klik Install untuk memulai proses instalasi
   - Tunggu sampai proses instalasi selesai
   - Setelah selesai klik **Finish**

## 3.2 Pengenalan Tag HTML

Tag merupakan kode yang digunakan untuk memperkenalkan pada web browser untuk apa text HTML yang ditulis. Tag dibutuhkan oleh HTML agar browser mengetahui apakah teks yang dituliskan sebagai list, paragraf, link, dan sebagainya.

### 3.2.1 Struktur Tag

Hampir keseluruhan tag terdiri dari tag pembuka dan tag penutup (container tag), hanya saja ada beberapa tag yang tidak menggunakan tag penutup atau disebut juga sebagai empty tag.

```
<tagname>Content goes here</tagname>
```

atau

```
<tagname>
```

Tag pada bagian Head:

- title
- script
- noscript
- link
- style
- base
- meta

Tag yang sering digunakan pada bagian Body:

- p
- a
- div
- list
- h
- table
- b

### 3.2.2 Attribute pada Tag

**Atribut** merupakan informasi tambahan yang digunakan didalam tag pembuka. Informasi ini bisa berupa instruksi untuk memberikan efek warna, ketebalan, dll. Atribut memiliki 2 bagian yaitu `nama dan nilai (name = “value”)`.
