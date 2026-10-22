JELAJAH INDONESIA — VERSI KODE RAPI

ISI WEBSITE
- index.html       : Beranda, navigasi, tempat gambar/video/audio
- daftar.html      : Daftar bullet dan numbering
- tabel.html       : Tabel destinasi wisata
- frame.html       : Halaman frame dengan menu dan area konten
- frame-menu.html  : Menu untuk halaman frame
- frame-beranda.html, frame-bali.html, frame-bromo.html, frame-toba.html
                  : Isi yang ditampilkan di frame
- iframe.html      : Halaman contoh iframe
- panduan.html     : Konten yang ditampilkan di iframe
- style.css        : Semua desain website, dipisah agar HTML mudah dibaca

CARA MENJALANKAN
1. Ekstrak file ZIP.
2. Buka folder dengan Visual Studio Code.
3. Ganti [Nama Lengkap] dan [NIM] di footer.
4. Buka index.html melalui Live Server.

CARA MENAMBAHKAN GAMBAR SENDIRI
1. Buat folder bernama images di dalam folder proyek.
2. Masukkan gambar, misalnya gambar-utama.jpg, bali.jpg, bromo.jpg, dan danau-toba.jpg.
3. Di index.html, cari komentar "TAMBAHKAN GAMBAR SENDIRI".
4. Hapus tanda komentar HTML yang membungkus tag img, lalu isi src dengan nama file yang benar.
5. Untuk kartu destinasi, ganti kotak placeholder dengan tag img. Contoh:
   <img class="card-image-placeholder" src="images/bali.jpg" alt="Pantai di Bali">

CARA MENAMBAHKAN VIDEO SENDIRI
1. Buat folder bernama videos.
2. Masukkan video MP4.
3. Di index.html, cari "TAMBAHKAN VIDEO SENDIRI".
4. Hapus komentar yang membungkus tag video, lalu sesuaikan nama file.

CARA MENAMBAHKAN SUARA SENDIRI
1. Buat folder bernama audio.
2. Masukkan file MP3.
3. Di index.html, cari "TAMBAHKAN AUDIO SENDIRI".
4. Hapus komentar yang membungkus tag audio, lalu sesuaikan nama file.
5. Autoplay dengan suara dapat diblokir browser; jika demikian, pengunjung perlu menekan tombol Play.

CATATAN
Tugas meminta 5 tautan dari homepage: Beranda, Daftar Wisata (bullet/numbering),
Tabel, Frame, dan IFrame. Semua menu ini sudah dibuat. Halaman Frame menggunakan
iframe modern sebagai pengganti frameset lama yang sudah tidak direkomendasikan.


GAMBAR DAN AUDIO YANG SUDAH DIPASANG
- images/danau-toba.jpg: gambar utama dan kartu Danau Toba.
- images/bromo.jpg: kartu Gunung Bromo.
- images/bali.jpg: kartu Bali.
- audio/gaze.mp3: musik latar dengan kontrol audio, autoplay, dan loop.

Catatan: browser dapat memblokir autoplay dengan suara. Jika musik tidak langsung berbunyi,
tekan tombol Play pada kontrol audio.
