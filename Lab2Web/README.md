# Lab2Web - Praktikum 2: HTML Lanjutan

| | |
|---|---|
| **Nama** | Erlina Dwi Artika |
| **Kelas** | I252A |
| **NIM** | 312510039 |
| **Mata Kuliah** | Pemrograman Web |

Repository ini berisi hasil Praktikum 2 (HTML Lanjutan): tabel, form dan berbagai jenis input,
semantic HTML, multimedia, dan validasi form dasar.

## Struktur Folder

```
Lab2Web/
├── index.html        # Latihan 1-8 (halaman utama, semantic HTML)
├── biodata.html      # Proyek mini: Form Biodata Mahasiswa
├── media/
│   ├── audio.mp3
│   └── video.mp4
├── screenshots/      # Bukti hasil praktik
└── README.md
```

## Cara Menjalankan

1. Clone / unduh repository ini.
2. Buka `index.html` (atau `biodata.html`) dengan browser, atau gunakan ekstensi Live Server di VS Code.

## Langkah Praktikum

### 1. Tabel Data Mahasiswa
Membuat tabel dengan `<table>`, `<tr>`, `<th>`, `<td>` dan 4 baris data mahasiswa.

![Tabel mahasiswa](screenshots/01-tabel-mahasiswa.png)

### 2. Tabel dengan thead, tbody, tfoot
Menambahkan `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` dan `colspan="2"` pada baris rata-rata.

![Tabel terstruktur](screenshots/02-tabel-thead-tbody-tfoot.png)

### 3. Form Registrasi Mahasiswa
Input `text`, `email`, `password`, `date`, tombol `submit` dan `reset`, setiap input memiliki `<label for>`.

![Form registrasi](screenshots/03-form-registrasi.png)

### 4. Radio Button dan Checkbox
Radio `jk` (satu pilihan) dan checkbox `skill` (banyak pilihan).

![Radio dan checkbox](screenshots/04-radio-checkbox.png)

### 5. Select dan Textarea
Dropdown program studi dan kolom alamat multi-baris.

![Select dan textarea](screenshots/05-select-textarea.png)

### 6. Validasi Form Dasar
Atribut `required`, `minlength`, `min`, `max`, dan `type="email"`. Pesan validasi muncul saat form tidak valid.

![Validasi kosong](screenshots/06a-validasi-kosong.png)
![Nama terlalu pendek](screenshots/06b-validasi-nama-pendek.png)
![Email tidak valid](screenshots/06c-validasi-email.png)
![Umur di bawah minimum](screenshots/06d-validasi-umur.png)

### 7. Semantic HTML
`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.

![Semantic HTML](screenshots/07-semantic-html.png)

### 8. Multimedia
Elemen `<audio controls>` dan `<video controls>`.

![Multimedia](screenshots/08-multimedia.png)

### 9. Proyek Mini: Biodata Mahasiswa (`biodata.html`)
Menggabungkan semantic HTML, tabel, form (text, email, date, radio, select, checkbox, textarea),
validasi dasar, dan satu elemen video.

![Biodata bagian atas](screenshots/09a-biodata-bagian-atas.png)
![Biodata bagian bawah](screenshots/09c-biodata-bagian-bawah.png)
![Validasi biodata](screenshots/09d-biodata-validasi.png)

### 10. Halaman Utama Gabungan (`index.html`)

![Index 1](screenshots/10a-index-final-bagian-1.png)
![Index 2](screenshots/10b-index-final-bagian-2.png)
![Index 3](screenshots/10c-index-final-bagian-3.png)
