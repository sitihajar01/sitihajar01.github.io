---
layout : post
tittle : "SCSS,and CSS"
---

penjelasan tentang SCSS, SASS and CSS

## 🔍 Pengertian

*CSS (Cascading Style Sheets)*  
Bahasa stylesheet standar di web. Memisahkan struktur (HTML) dari presentasi (tampilan visual).

*SASS (Syntactically Awesome Style Sheets)*  
Preprocessor CSS yang menambah sintaks seperti variables, nesting, mixins, dan lain-lain. Mengompilasi ke CSS biasa.

*SCSS (Sassy CSS)*  
Varian SASS dengan sintaks mirip CSS (kurung kurawal & titik koma).

<p style="float:right; margin:0 0 1rem 1rem; width:200px;">
  <img src="/assets/images/Gambar css.jpg" alt="CSS & Sass Logo" style="width:100%; border-radius:8px;">
</p>

---

## ⚙ Fungsi Utama

1. *Warna & Tipografi*  
   Mengatur warna teks/latar, jenis font, ukuran, ketebalan, dan spasi huruf.

2. *Layout & Posisi*  
   Menentukan lebar/tinggi, margin, padding, serta posisi elemen (flexbox, grid, float).

3. *Responsivitas*  
   Media queries untuk menyesuaikan tampilan di berbagai ukuran layar.

4. *Animasi & Transisi*  
   Membuat efek halus seperti hover, keyframes, dan transform.

---

## 🛠 Contoh Kode CSS

```css
/* style.css */
:root {
  --primary-color: #3498db;
  --font-family: 'Segoe UI', sans-serif;
}

body {
  font-family: var(--font-family);
  color: #333;
  margin: 0;
  padding: 0;
}

header {
  background-color: var(--primary-color);
  padding: 1rem;
  text-align: center;
  color: white;
}

.card {
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  border-radius: 8px;
  padding: 1rem;
  margin: 1rem 0;
}