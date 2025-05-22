---
title: "Belajar CSS Dasar"
excerpt: "Pengenalan Dasar CSS (Cascading Style Sheets)"
coverImage: "/assets/blog/css/css.png"
date: "2025-05-22T05:35:07.322Z"
author:
  name: Fadhil Akbar Djunaedi
  picture: "/assets/blog/authors/profile4.jpeg"
ogImage:
  url: "/assets/blog/hello-world/cover.jpg"
---

# Pengenalan Dasar CSS (Cascading Style Sheets)

## Apa Itu CSS?

CSS adalah singkatan dari **Cascading Style Sheets**. CSS digunakan untuk mengatur tampilan dan gaya dari elemen HTML di sebuah halaman web, seperti warna, ukuran teks, posisi elemen, dan layout secara keseluruhan.

Tanpa CSS, halaman web hanya akan terlihat polos karena HTML hanya mengatur struktur, bukan tampilan.

---

## Mengapa CSS Penting?

Dengan CSS, kita bisa:

- Membuat desain halaman yang menarik dan responsif.
- Memisahkan antara **struktur (HTML)** dan **gaya (CSS)**.
- Mengatur satu gaya untuk banyak halaman (reusable).
- Menghemat waktu dan kode (lebih efisien daripada menambahkan style di setiap tag HTML).

---

## Cara Menyisipkan CSS

CSS bisa ditulis dengan 3 cara:

### 1. Inline CSS

CSS langsung ditulis di dalam elemen HTML menggunakan atribut `style`.

```html
<p style="color: blue;">Teks ini berwarna biru.</p>
```

### 2. Internal CSS

CSS ditulis di dalam tag <style> di bagian <head> dokumen HTML.

```html
<head>
  <style>
    p {
      color: green;
    }
  </style>
</head>
```

### 3. External CSS

CSS ditulis di file terpisah (misalnya style.css) dan dihubungkan melalui tag <link>.

```html
<link rel="stylesheet" href="style.css" />
```
