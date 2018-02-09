# Sistem-Integrasi-Kelas-SMK
Pada repositori ini kita coba membangun sebuah server yang akan kita gunakan sebagai sistem terintegrasi untuk mengelola kelas agar terdistribusi, setiap tugas, materi dan lain sebagainya

<b>Step 1:</b> Berikut adalah Jalur Jaringan yang kita gunakan
<img src="https://github.com/septiyadii/Sistem-Integrasi-Kelas-SMK/blob/master/1.png"/>

Dari jalur jaringan diatas kita simpulkan  bahwa internet kita bersumber pada jaringan local dengan sistematika jaringan bersumber dari jaringan ISP atau penyedia layanan internet local misalkan (Telkom, BizNet, Dsb).

Selanjutnya pastikan sudah menyeting Wireless untuk Akses internet untuk Guru dan Para Murid, dan kita coba sediakan sebuah server dengan basis linux pada keluarga Debian, bisa (Linux Mint, Ubuntu, Ataupun yang lain disini kita gunakan OS Linux Mint) dan berikut adalah server yang kita buat dan didalamnya ada:

- SSH Server
- FTP Server
- Samba Server

<img src="https://github.com/septiyadii/Sistem-Integrasi-Kelas-SMK/blob/master/2.png"/>

Kita asumsikan untuk jaringan sudah siap pakai, sampai penggunaan akses internet menggunakan Wireless, selanjutnya kita coba setting server seperti berikut:

- Persiapan Installasi Server di Komputer (Laptop, Komputer Desktop, Komputer Server)
Kali ini kita akan menginstallkan sebuah sistem operasi OS Linux berbasis atau distro Ubuntu Server 16.04.03 LTS, dari itu kita akan memasangkan beberapa service agar kelas dapat dimaksimalkan dengan baik, yaitu diataranya:<br><br>
<b>Bag. 1:</b> Menginstall OS Ubuntu Server di VirtualBox bisa lihat (<a href="https://github.com/septiyadii/Course-of-Website/wiki/Materi-K:-Membangun-Web-Server-di-VM-Ubuntu-Server-16.04.03-LTS">Disini</a>)<br><br>
Setelah terinstall pastikan komputer server terkonseksi internet dan sudah di set ip static, untuk itu jika belum silahkan atur pengaturannya seperti berikut:<br><br>
<b>Bag. 2:</b> Mengatur IP Static pada Server Ubuntu (<a href="https://github.com/septiyadii/Course-of-Website/wiki/Materi-I:-Mengatur-IP-Static-Pada-Komputer-Server">Disini</a>)<br><br>
Jika sudah kemudian kita siapkan beberapa folder penting sebagai penunjang kelas yang terdistribusi yaitu diantaranya adalah:<br>
a) Folder `Tugas`<br>
b) Folder `Pengumpulan Tugas`<br>
c) Folder `Praktikum`<br>
d) Folder `Artikel`<br>
e) Folder `Project`<br>
