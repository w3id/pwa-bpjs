*Status: Boilerplate aplikasi masih dalam pengembangan.*

# Cek Fasilitas Kesehatan BPJS
Progressive web app untuk mengecek ketersedian fasilitas kesehatan BPJS yang fokus pada kemudahan penggunaan untuk menemukan fasilitas kesehatan yang dibutuhkan oleh peserta BPJS.

Aplikasi ini dibuat sebagai proyek terbuka untuk komunitas web developer agar bisa belajar bagaimana mengembangkan web modern yang fokus bagi kenyamanan pengguna.

## Stack Dan Anggaran Kecepatan
Aplikasi ini dikembangkan berbasis web component. Sehingga untuk setiap fungsi yang dikembangkan harus dapat digunakan sebagai web component. Walaupun dalam pengembangannya setiap component tidak dibatasi menggunakan framework atau library tertentu akan tetapi aplikasi ini akan menerapkan performance budget maksimal 50KB untuk total ukuran JavaScript yang di-load pertama kali di setiap halaman. Sehingga penambahan fitur akan dites untuk tidak melebihi 50KB setelah bundling webpack, dan setiap pull request yang tidak memenuhi persyaratan maksimal 50KB bundling JavaScript akan di-reject. Penerapan anggaran kecepatan maksimal 50KB ini untuk memastikan aplikasi masih bisa digunakan di jaringan 2G.

## Cara Kontribusi
Semua pengembang bisa memberikan kontribusi baik itu berupa masukan, melaporkan bug, atau bahkan kontribusi kode. Untuk lebih jelasnya silakan membaca [dokumen kontribusi ini](https://github.com/w3id/pwa-bpjs-cek-fasilitas/blob/master/docs/CONTRIBUTING.md).
