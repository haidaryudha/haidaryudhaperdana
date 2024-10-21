# Laporan Praktikum
# Cara Membuat Repository di GitHub

## Langkah-langkah Membuat Repository

1. *Login ke GitHub*
   - Buka [GitHub](https://github.com) dan masuk ke akun Anda.
   ![Gambar 1](SS Tugas/SS1.png)

2. *Buat Repository Baru*
   - Klik tombol "+" di pojok kanan atas dan pilih "New repository".

3. *Isi Informasi Repository*
   - *Repository Name*: Masukkan nama repository yang diinginkan (misalnya: Praktikum3).
   - *Description*: (Opsional) Tambahkan deskripsi singkat tentang repository Anda.
   - *Public/Private*: Pilih apakah repository akan bersifat publik atau privat.
   - Centang opsi "Initialize this repository with a README" jika ingin memulai dengan file README.

4. *Klik "Create repository"*
   - Setelah semua informasi diisi, klik tombol "Create repository" untuk membuat repository baru.

5. *Clone Repository (Opsional)*
   - Buka terminal di komputer Anda.
   - Jalankan perintah berikut untuk meng-clone repository ke lokal:
     bash
     git clone https://github.com/username/Praktikum3.git
     
   - Ganti username dengan nama pengguna GitHub Anda.

6. *Buat Folder Proyek*
   - Masuk ke folder proyek yang baru di-clone:
     bash
     cd Praktikum3
     

7. *Tambahkan File*
   - Buat file baru di dalam folder tersebut, misalnya program.py dan README.md.

8. *Inisialisasi Git (Jika Belum)*
   - Jika belum, jalankan perintah berikut untuk menginisialisasi git:
     bash
     git init
     

9. *Tambah dan Commit Perubahan*
   - Tambahkan semua perubahan yang telah dibuat:
     bash
     git add .
     
   - Commit perubahan dengan pesan:
     bash
     git commit -m "Menambahkan file awal"
     

10. *Push ke GitHub*
    - Push perubahan ke repository di GitHub:
      bash
      git push -u origin main
      

## Flowchart

### Penjelasan:
1. *Mulai*: Proses dimulai.
2. *Input bilangan1*: Pengguna diminta untuk memasukkan bilangan pertama.
3. *Input bilangan2*: Pengguna diminta untuk memasukkan bilangan kedua.
4. *Input bilangan3*: Pengguna diminta untuk memasukkan bilangan ketiga.
5. *Bandingkan bilangan1 dengan bilangan2*: Jika bilangan1 lebih besar atau sama dengan bilangan2, lanjutkan ke langkah berikutnya. Jika tidak, lanjutkan ke langkah 6.
6. *Bandingkan bilangan1 dengan bilangan3*: Jika bilangan1 lebih besar atau sama dengan bilangan3, maka bilangan1 adalah yang terbesar. Jika tidak, bilangan3 adalah yang terbesar.
7. *Bandingkan bilangan2 dengan bilangan3*: Jika bilangan2 lebih besar atau sama dengan bilangan3, maka bilangan2 adalah yang terbesar. Jika tidak, bilangan3 adalah yang terbesar.
8. *Output*: Tampilkan bilangan terbesar yang ditemukan.
9. *Selesai*: Proses berakhir.


