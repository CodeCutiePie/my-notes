---
layout: post
title: "Panduan Dasar Memulai Jekyll"
date: 2024-10-26
categories:
  - Panduan
  - Web Development
tags:
  - jekyll
  - pemula
  - panduan
excerpt: Panduan dasar untuk memulai proyek website menggunakan Jekyll.
status: published
thumbnail: /assets/images/jekyll-guide-thumbnail.jpg
post: true
---

# Panduan Dasar Memulai Jekyll

Bagi kamu yang ingin **memulai perjalanan di dunia pengembangan web** dengan Jekyll, artikel ini akan membahas langkah-langkah awal yang perlu kamu ketahui.

## Mengapa Memilih Jekyll?

Jekyll adalah pilihan tepat bagi pemula yang ingin belajar tentang pengembangan web karena:

- **Mudah Dipelajari:** Dengan struktur sederhana, Jekyll cocok untuk pemula.
- **Cepat dan Ringan:** Hasilkan halaman statis yang cepat diakses.
- **Kustomisasi yang Fleksibel:** Mudah untuk mengubah dan menyesuaikan tampilan website.

## Langkah-Langkah Memulai Proyek Jekyll

1. **Instalasi Jekyll:** Pastikan kamu sudah menginstal Ruby dan Jekyll di komputer kamu. Untuk instalasi, jalankan:
   ```bash
   gem install jekyll bundler
   ```

2. **Membuat Proyek Baru:** Buat proyek Jekyll baru dengan perintah:
   ```bash
   jekyll new my-website
   ```

3. **Menjalankan Website Lokal:** Coba jalankan proyek kamu secara lokal untuk melihat hasilnya:
   ```bash
   bundle exec jekyll serve
   ```
   Setelah itu, buka [http://localhost:4000](http://localhost:4000) di browser kamu!

## Menambahkan Postingan

Untuk menambahkan postingan baru, buat file Markdown di dalam folder `_posts` dengan format nama `tahun-bulan-tanggal-judul.md`.

Contoh:
```markdown
2024-10-26-panduan-jekyll.md
```

Isi file tersebut dengan metadata seperti ini:

```markdown
---
layout: post
title: "Panduan Memulai Jekyll"
date: 2024-10-26
categories: Panduan
tags: jekyll, panduan, pemula
---
```

## Selamat Mencoba!

Jekyll memberikan banyak kebebasan untuk berkreasi. Semoga panduan ini membantumu dalam memulai proyek web pertama kamu dengan Jekyll. Sampai bertemu di postingan selanjutnya!

![Panduan Thumbnail](/assets/images/jekyll-guide-thumbnail.jpg)