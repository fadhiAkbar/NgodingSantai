---
title: "Pengenalan Tailwind"
excerpt: "Pengenalan Dasar CSS (Cascading Style Sheets)"
coverImage: "/assets/blog/css/tailwind.png"
date: "2025-05-22T05:35:07.322Z"
author:
  name: Fadhil Akbar Djunaedi
  picture: "/assets/blog/authors/profile4.jpeg"
ogImage:
  url: "/assets/blog/css/tailwind.png"
---

# Panduan Lengkap Tailwind CSS

## Apa Itu Tailwind CSS?

**Tailwind CSS** adalah framework CSS utility-first yang memungkinkan kita membangun antarmuka (UI) dengan cepat dan efisien hanya menggunakan class-class yang sudah disediakan.

Berbeda dengan framework seperti Bootstrap yang menyediakan komponen siap pakai, Tailwind memberi kita _building blocks_ dalam bentuk class utility seperti `p-4`, `text-center`, `bg-blue-500`, dll.

---

## Mengapa Memilih Tailwind CSS?

- 🚀 **Cepat dan efisien**: Class utility mempermudah pembuatan desain tanpa menulis CSS manual.
- 🧠 **Customizable**: Mudah dikustomisasi dengan `tailwind.config.js`.
- 🎯 **Desain konsisten**: Desain mengikuti skala ukuran dan warna yang sudah ditentukan.
- 🧩 **Tanpa perlu keluar dari HTML**: Semua styling langsung di class HTML.

---

## Cara Menggunakan Tailwind CSS

### 1. Instalasi via CDN (untuk prototipe)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <h1 class="text-3xl font-bold text-blue-500">Hello Tailwind!</h1>
  </body>
</html>
```

### 2. Instalasi via NPM (Proyek Real)

```bash
npm install -D tailwindcss
npx tailwindcss init
```

# Konfigurasi file Tailwind:

```js
// tailwind.config.js
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

# Import Tailwind di file CSS:

```css
/* styles.css */
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Contoh Penggunaan

```html
<div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md">
  <h1 class="text-2xl font-bold text-gray-900">Judul Artikel</h1>
  <p class="text-gray-600 mt-2">Ini adalah isi kontennya.</p>
</div>
```
