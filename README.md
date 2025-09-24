# Lab-1 | Tag Dasar HTML

Nama : Tiara Hayatul Khoir

Kelas : TI.24.A.5

NIM : 312410474

Mata Kuliah : Pemrograman Web



## Jawab Pertanyaan Berikut

### 1. Apa yang terjadi jika ada error penulisan tag HTML?
Jika terjadi kesalahan penulisan tag HTML, browser umumnya tetap berusaha menampilkan halaman. Namun, tampilan halaman tersebut bisa menjadi tidak sesuai dengan yang diharapkan. Beberapa elemen mungkin tidak muncul, tata letak berantakan, atau fungsi tertentu tidak berjalan sebagaimana mestinya.

### 2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
Tag `<p>` digunakan untuk membuat sebuah paragraf baru, di mana secara default terdapat jarak (spasi) sebelum dan sesudah paragraf. Sementara itu, tag `<br>` hanya digunakan untuk memindahkan teks ke baris berikutnya tanpa memberikan jarak tambahan seperti pada paragraf.

### 3. Apa perbedaan atribut 'title' dan 'alt' pada tag `<img>`, berikan penjelasannya!
Atribut title biasanya muncul kayak tooltip waktu kursor diarahkan ke gambar, jadi sifatnya lebih ke info tambahan. Sementara alt itu teks pengganti yang nongol kalau gambar gagal dimuat, plus berguna banget buat aksesibilitas (dibaca screen reader). Jadi title lebih buat “hiasan/info ekstra”, alt lebih penting secara fungsional.

### 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan Penjelasannya!
Kalau mau gambar tetep proporsional, biasanya cukup isi salah satu aja, misalnya width. Karena kalau dua-duanya diisi tapi gak sesuai rasio aslinya, gambar bisa jadi gepeng atau ketarik. Jadi biar aman, atur satu atribut aja dan biarkan browser otomatis nyesuaiin sisanya.

### 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi `( _blank, _self, _top, _parent )`, apa yang terjadi pada masing-masing nilai antribut tersebut?
- `_blank` → link kebuka di tab baru (sering dipake biar halaman utama gak ketutup).

- `_self` → link kebuka di tab yang sama, ini default-nya.

- `_top` → link kebuka di jendela paling atas, biasanya kepake kalau lagi mainan frame/iframe.

- `_parent` → link kebuka di frame induk, satu tingkat di atas halaman sekarang.



## Langkah-langkah Praktikum

### 1. Langkah 1 – Membuat File HTML Dasar
Saya membuat file baru bernama `lab1_tag_dasar.html` dengan struktur HTML yang ada pada modul.  
Setelah itu file ini akan digunakan untuk menambahkan elemen-elemen HTML berikutnya.  

![Struktur HTML Dasar](https://github.com/tir890/Lab-1-Tag-Dasar-HTML/blob/db12d59c84cba4f67ce8ce9fa408d879d14548a3/Langkah%200.png)

### 2. Langkah 2 – Membuat Paragraf
Saya menambahkan dua paragraf menggunakan tag `<p>`.  
Paragraf pertama berisi pengenalan singkat, dan paragraf kedua berisi contoh teks tambahan.  
Saya juga mencoba atribut `align` (center, right, left, justify) untuk melihat perbedaan posisi teks.  

![Paragraf HTML](https://github.com/tir890/Lab-1-Tag-Dasar-HTML/blob/0ca9b799f58256c0b5548905927f5bd9386c4962/Langkah%202.png)

### 3. Langkah 3 – Menambahkan Judul
Saya menambahkan heading `<h1>` sebagai judul utama, dan `<h2>` sebagai subjudul.  
Heading membuat tampilan halaman lebih terstruktur dan mudah dibaca.  

![Heading HTML](https://github.com/tir890/Lab-1-Tag-Dasar-HTML/blob/bade7b5ab13dc01a03b9a98c66648d9622049cf8/Langkah%203.png)

### 4. Membuat Paragraf
Selanjutnya membuat beberapa paragraf sederhana sebagai contoh berikut,
```html
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```
Setelah itu simpan kembali perubahannya, dan lakukan refresh pada web browser untuk melihat hasilnya.

### 5. Tampilan Paragraf pada Browser
![foto]

### 6. Mengatur Atribut





