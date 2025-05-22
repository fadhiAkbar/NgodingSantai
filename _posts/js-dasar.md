---
title: "Belajar JS Dasar"
excerpt: "Pengenalan Dasar CSS (Cascading Style Sheets)"
coverImage: "/assets/blog/js/js.png"
date: "2025-05-22T05:35:07.322Z"
author:
  name: Fadhil Akbar Djunaedi
  picture: "/assets/blog/authors/profile4.jpeg"
ogImage:
  url: "/assets/blog/js/js.png"
---

# Pengenalan Dasar JavaScript

## Apa Itu JavaScript?

**JavaScript (JS)** adalah bahasa pemrograman yang digunakan untuk membuat halaman web menjadi interaktif. Jika HTML digunakan untuk struktur dan CSS untuk tampilan, maka JavaScript berperan sebagai logika dan interaktivitas, seperti:

- Menangani klik tombol
- Validasi form
- Animasi
- Mengambil data dari server (AJAX/fetch)
- Membuat aplikasi SPA (Single Page Application)

---

## Mengapa Harus Belajar JavaScript?

JavaScript adalah bahasa pemrograman utama di sisi **client (browser)** dan bisa juga digunakan di sisi **server** dengan teknologi seperti **Node.js**. Semua browser modern mendukung JavaScript tanpa perlu plugin tambahan.

---

## Cara Menulis JavaScript

### 1. Inline JS (langsung di HTML)

```html
<button onclick="alert('Halo!')">Klik Saya</button>
```

### 2. Internal JS di dalam tag script

```html
<script>
  console.log("Halo dari JavaScript");
</script>
```

### 3. External JS (di file terpisah)

```html
<script src="script.js"></script>
```

### Variabel di JavaScript

# JavaScript memiliki tiga cara mendeklarasikan variabel:

```js
var nama = "Andi"; // versi lama
let umur = 20; // bisa diubah
const gender = "L"; // tidak bisa diubah
```
