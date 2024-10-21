# Laporan Praktikum
# Cara Membuat Repository di GitHub

## Langkah-langkah Membuat Repository

1. *Login ke GitHub*
   - Buka [GitHub](https://github.com) dan masuk ke akun Anda.

   ![Image](https://github.com/user-attachments/assets/87e817a7-829a-4602-aca0-be056d540eca)

2. *Buat Repository Baru*
   - Klik tombol "+" di pojok kanan atas dan pilih "New repository".

     ![Image](https://github.com/user-attachments/assets/c495b49d-5233-43f2-9cb6-0d8e0d7010bd)

3. *Isi Informasi Repository*
   - *Repository Name*: Masukkan nama repository yang diinginkan (misalnya: Praktikum3).
   - *Description*: (Opsional) Tambahkan deskripsi singkat tentang repository Anda.
   - *Public/Private*: Pilih apakah repository akan bersifat publik atau privat.
   - Centang opsi "Initialize this repository with a README" jika ingin memulai dengan file README.

     ![Image](https://github.com/user-attachments/assets/be1ded9d-a4a6-4329-81c2-5326cad2678e)
   

4. *Klik "Create repository"*
   - Setelah semua informasi diisi, klik tombol "Create repository" untuk membuat repository baru.

     ![Image](https://github.com/user-attachments/assets/d3935e6c-24ab-4200-a340-9c66f633b075)



## Flowchart
![Image](https://github.com/user-attachments/assets/48385c54-3434-4153-a0e7-f5223baea260)


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


## flowchart di atas dalam bentuk Codingan

![Image](https://github.com/user-attachments/assets/096a8329-645d-42b9-a849-1d3734cbbf91)

## Penjelasan Fungsi cari_bilangan_terbesar_dari_tiga()

def cari_bilangan_terbesar_dari_tiga():

Definisi Fungsi: Baris ini mendefinisikan fungsi dengan nama cari_bilangan_terbesar_dari_tiga. Kata kunci def digunakan untuk mendefinisikan fungsi. Fungsi ini tidak memiliki parameter.
python

    A = float(input("Masukkan bilangan A: "))
    B = float(input("Masukkan bilangan B: "))
    C = float(input("Masukkan bilangan C: "))
Input Bilangan: Tiga bilangan (A, B, dan C) diminta dari pengguna menggunakan fungsi input(). Input ini diubah menjadi tipe float untuk memungkinkan pengguna memasukkan bilangan pecahan.
python

    if A > B:
Pengkondisian Pertama: Memeriksa apakah A lebih besar dari B. Jika benar, maka kita perlu melakukan pemeriksaan lebih lanjut untuk menentukan apakah A adalah yang terbesar.
python

        if A > C:
            terbesar = A
Pengkondisian Kedua: Jika A lebih besar dari B, maka kita memeriksa apakah A juga lebih besar dari C. Jika ya, maka A adalah bilangan terbesar, dan kita menyimpan nilainya dalam variabel terbesar.
python

        else:
            terbesar = C
Else dari Pengkondisian Kedua: Jika A tidak lebih besar dari C, maka C adalah bilangan terbesar.
python
Salin kode
    else:
Else dari Pengkondisian Pertama: Jika A tidak lebih besar dari B, berarti B lebih besar atau sama dengan A. Kita perlu memeriksa B terhadap C.
python

        if B > C:
            terbesar = B
Pengkondisian Ketiga: Jika B lebih besar dari C, maka B adalah bilangan terbesar.
python

        else:
            terbesar = C
Else dari Pengkondisian Ketiga: Jika B tidak lebih besar dari C, maka C adalah bilangan terbesar.
python

    print(f"Bilangan terbesar adalah: {terbesar}")
Menampilkan Hasil: Setelah semua pemeriksaan selesai, program mencetak nilai dari terbesar, yang merupakan bilangan terbesar dari ketiga bilangan yang dimasukkan.
python

cari_bilangan_terbesar_dari_tiga()

Panggilan Fungsi: Baris ini memanggil fungsi yang telah didefinisikan, sehingga eksekusi fungsi dimulai.

