---
layout : post
tittle : "YML or YAML"
---

penjelasan tentang YML or YAML.

YAML (*YAML Ain’t Markup Language*) adalah bahasa serialisasi data yang dirancang agar mudah dibaca manusia.  
YAML biasanya digunakan untuk file konfigurasi modern seperti:

- Jekyll  
- Docker  
- Kubernetes  
- GitHub Actions  
- dan lainnya

> *Catatan:* Ekstensi .yml dan .yaml sebenarnya sama saja; keduanya hanya membungkus teks berformat YAML.

<p align="center">
  <img src="/assets/images/Gambar yaml-logo.jpg" alt="Gambar YAML-Logo" width="150" style="margin: 10px;">
  <img src="/assets/images/Gambar yaml-logo II.jpg" alt=" Gambar YAML-Logo II" width="150" style="margin: 10px;">
</p>

---

## Kelebihan YAML

1. *Mudah Dibaca*  
   Mirip bahasa manusia, tanpa banyak tanda kurung atau koma.

2. *Indentasi Sederhana*  
   Mengandalkan spasi untuk menandai struktur, meminimalkan kesalahan tanda baca.

3. *Dukungan Data Kompleks*  
   Bisa menyimpan list, mapping (dictionary), bahkan struktur bersarang (nested structures).

4. *Ekosistem Luas*  
   Digunakan di banyak tools modern seperti Jekyll, GitHub Actions, Kubernetes, Docker, dll.

---

## Contoh YAML Sederhana

```yaml
site:
  title: My Blog
  description: Blog pribadi untuk belajar YAML
posts:
  - title: "Belajar YAML"
    date: 2025-03-14
    tags:
      - yaml
      - konfigurasi