# Lab-1 | Tag Dasar HTML

Nama : Tiara Hayatul Khoir

Kelas : TI.24.A.5

NIM : 312410474

Mata Kuliah : Pemrograman Web

## Jawab Pertanyaan Berikut

### 1. Apa yang terjadi jika ada error penulisan tag HTML?
Jika terjadi kesalahan penulisan tag HTML, browser umumnya tetap berusaha menampilkan halaman. Namun, tampilan halaman tersebut bisa menjadi tidak sesuai dengan yang diharapkan. Beberapa elemen mungkin tidak muncul, tata letak berantakan, atau fungsi tertentu tidak berjalan sebagaimana mestinya.

### 2. Apa perbedaan dari tag <p> dengan tag <br> ?
Tag <p> digunakan untuk membuat sebuah paragraf baru, di mana secara default terdapat jarak (spasi) sebelum dan sesudah paragraf. Sementara itu, tag <br> hanya digunakan untuk memindahkan teks ke baris berikutnya tanpa memberikan jarak tambahan seperti pada paragraf.

### 3. Apa perbedaan atribut 'title' dan 'alt' pada tag <img>?
Atribut title biasanya muncul kayak tooltip waktu kursor diarahkan ke gambar, jadi sifatnya lebih ke info tambahan. Sementara alt itu teks pengganti yang nongol kalau gambar gagal dimuat, plus berguna banget buat aksesibilitas (dibaca screen reader). Jadi title lebih buat “hiasan/info ekstra”, alt lebih penting secara fungsional.

### 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan Penjelasannya!
Kalau mau gambar tetep proporsional, biasanya cukup isi salah satu aja, misalnya width. Karena kalau dua-duanya diisi tapi gak sesuai rasio aslinya, gambar bisa jadi gepeng atau ketarik. Jadi biar aman, atur satu atribut aja dan biarkan browser otomatis nyesuaiin sisanya.

### 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
`_blank` → link kebuka di tab baru (sering dipake biar halaman utama gak ketutup).

`_self` → link kebuka di tab yang sama, ini default-nya.

`_top` → link kebuka di jendela paling atas, biasanya kepake kalau lagi mainan frame/iframe.

`_parent` → link kebuka di frame induk, satu tingkat di atas halaman sekarang.
