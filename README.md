# Lab1Web - Praktikum 1: HTML Dasar

Repositori ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Web** pada **Praktikum 1: HTML Dasar**.

---

## 👤 Data Mahasiswa
- **Nama** : [Satrio Erlangga]
- **NIM** : [312510006]
- **Kelas** : [I253C]
- **Program Studi** : Teknik Informatika
- **Fakultas** : Teknik
- **Instansi** : Universitas Pelita Bangsa

---

## 📁 Struktur Folder
```text
Lab1Web/
├── index.html
├── halaman2.html
├── README.md
└── images/
    └── profil.jpg
---

## 📸 Langkah-Langkah Praktikum & Screenshot Hasil

### 1. Struktur Dasar HTML5
Membuat kerangka dasar dokumen HTML yang terdiri dari deklarasi `<!DOCTYPE html>`, elemen `<html>`, `<head>`, dan `<body>`.

**Kode & Tampilan Browser:**
[<img width="715" height="148" alt="Cuplikan layar 2026-09-27 001704" src="https://github.com/user-attachments/assets/453b450a-4ee2-495c-9cae-6d3e049d4387" />
] [<img width="959" height="505" alt="Cuplikan layar 2026-09-27 001759" src="https://github.com/user-attachments/assets/87c9a74e-9797-4363-8b16-a805730818a0" />
]

---

### 2. Membuat Paragraf
Menambahkan beberapa paragraf teks menggunakan tag `<p>` untuk menampilkan teks deskripsi praktikum.

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 2 di sini / Drag Gambar ke sini]

---

### 3. Menambahkan Judul (Heading)
Menambahkan judul utama menggunakan tag `<h1>` dan sub-judul menggunakan tag `<h2>`.

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 3 di sini / Drag Gambar ke sini]

---

### 4. Memformat Teks
Mengubah gaya teks menggunakan tag pemformatan seperti `<b>` (tebal), `<i>` (miring), `<strong>` (penekanan), `<sub>` (subscript), dan `<sup>` (superscript).

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 4 di sini / Drag Gambar ke sini]

---

### 5. Menyisipkan Gambar
Menampilkan gambar profil pada halaman web menggunakan tag `<img>` dengan menentukan path gambar pada atribut `src`, ukuran lebar `width`, serta teks alternatif `alt`.

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 5 di sini / Drag Gambar ke sini]

---

### 6. Menambahkan Hyperlink
Membuat navigasi menu menggunakan tag `<a>` yang menghubungkan tautan internal (`halaman2.html`) dan tautan eksternal (Google).

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 6 di sini / Drag Gambar ke sini]

---

### 7. Menambahkan List (Daftar)
Membuat daftar keahlian tanpa urutan (*Unordered List*) menggunakan tag `<ul>` dan daftar langkah belajar berurutan (*Ordered List*) menggunakan tag `<ol>`.

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 7 di sini / Drag Gambar ke sini]

---

### 8. Menambahkan Komentar
Menambahkan komentar kode menggunakan sintaks `<!-- komentar -->` sebagai catatan internal pemrogram yang tidak muncul di browser.

**Kode & Tampilan Browser:**
[Taruh Screenshot Langkah 8 di sini / Drag Gambar ke sini]

---

### 9. Penggabungan Semua Elemen (Hasil Akhir)
Menggabungkan seluruh elemen dasar HTML yang telah dipelajari menjadi satu halaman utuh **Profil Mahasiswa** pada file `index.html`.

**Tampilan Akhir Web:**
[Taruh Screenshot Langkah 9 / Hasil Akhir di sini]

---

## 💻 Kode Utama (`index.html`)

```html
<!DOCTYPE html>
<html>
<head>
    <title>Profil Mahasiswa</title>
</head>
<body>

    <nav>
        <a href="index.html">Beranda</a> |
        <a href="halaman2.html">Halaman 2</a> |
        <a href="[https://www.google.com](https://www.google.com)" target="_blank">Website Eksternal</a>
    </nav>
    <hr>

    <h1>Profil Mahasiswa</h1>
    <img src="images/profil.jpg" width="200" alt="Foto profil mahasiswa">

    <h2>Data Diri</h2>
    <p>Nama: Satrio Erlangga</p>
    <p>Program Studi: Teknik Informatika</p>
    <p>Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan HTML.</p>

    <h2>Keahlian</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Target Belajar</h2>
    <ol>
        <li>Menguasai HTML</li>
        <li>Menguasai CSS</li>
        <li>Menguasai JavaScript</li>
    </ol>

</body>
</html>
