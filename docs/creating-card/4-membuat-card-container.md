---
sidebar_position: 4
---

# 4. Membuat Card Container

Membuat study case berupa card, kita bisa memanfaatkan container tag div pada HTML untuk membentuk cardnya. Serta memberikan styling menggunakan CSS agar tampak sesuai dengan mockup study case

## 4.1 Pengenalan DIV

**Division atau dikenal div** merupakan sebuah container tag yang dapat membagi konten di dalam halaman web seperti `teks, image, header, footer, navigation, dll`.
Div adalah tag yang paling berguna dalam pengembangan web karena membantu kita untuk memisahkan data di halaman web dan kita dapat membuat bagian tertentu untuk data atau fungsi tertentu di halaman web

```html {6-8} title="index.html"
<!DOCTYPE html>
<head>
  <title>Creating Card</title>
</head>
<body>
  <div>
    <!-- Content goes here -->
  </div>
</body>
</html>
```

## 4.2 Memberikan Style pada Card

**Cascading Style Sheets (CSS)** adalah kumpulan perintah yang digunakan untuk menggambarkan tampilan dari sebuah halaman situs web dalam bahasa mark-up. Bahasa markup atau bahasa markup adalah bahasa pemrograman bahasa yang biasa digunakan untuk membuat website.
Style yang bisa kita gunakan untuk menstyling card yang sudah dibuat adalah `border dan margin`.
Border kita gunakan untuk memberikan styling terkait tipe, warna, dan ketebalan dari border.

```html {6-15} title="index.html"
<!DOCTYPE html>
<head>
  <title>Creating Card</title>
</head>
<body>
  <div style="
    margin-top: 150px;
    width: 350px;
    border-radius: 16px;
    padding: 15px;
    border: 1px solid #00000033;
    box-shadow: 0px 0px 20px #00000040;
    ">
    <!-- Content goes here -->
  </div>
</body>
</html>
```
