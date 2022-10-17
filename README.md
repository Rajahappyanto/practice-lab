## **CARA PENGGUNAAN GIT BESERTA LANGKAH LANGKAHNYA**

# BERIKUT INI ADALAH LANGKAH LANGKAH MENGGUNAKAN GIT

### 1. **MASUK GIT**
untuk login ke git, bisa menggunakan git hub, jika anda sudah memilikinya silahkan daftarkan diri lewat **command prompt** atau **command line** ,kemudian masukkan perintah ini
---
$ git config --global user.name (input your name)
$ git config --global user.email (input your email)
---
selanjutnya untuk memastikan proses login berhasil, ketik perintah
---

$ git config --list
---

![scs1](pict_practice/scs1.png)
### 2. **MASUK GITHUB**
Untuk menggunakan git buat akun gihub  terlebih dulu. Github dan Git mempunyai hubungan khusus yaitu git sebagai version control sistem sedangkan github sebagai penyimpan kode pemograman.

![scs2](pict_practice/scs2.jpg)
### 3. **BUAT REPOSITORY**
setelah membuat akun github kini saat nya untuk membuat repository. klik tombol "new" pada menu **repository** untuk membuat repository baru. langkah langkahnya adalah sebagai berikut.
1) isi bagian nama repository
2) isi deskripsi
3) jenis repository publik atau privat
![scs3](pict_practice/scs3.jpg)
### 4. **BUAT FOLDER DI WINDOWS**
Selanjutnya membuat folder pada local disk komputer untuk menyimpan file dari repository yang telah di buat.
### 5. **BUKA FOLDER MENGGUNAKAN GIT BASH**
Buka folder tsb dengan git bash, dengan cara click kanan, show more option, lalu click gitbash here.
![scs4](pict_practice/scs4.png)
### 6. **UBAH FOLDER MENJADI REPODITORY**
ubah folder menggunakan perintah 
---

$ git init
---


### 7. **TAMBAHKAN FILE REPOSITORY, BUAT KOMITMEN, HUBUNGKAN FILE KE REPOSITORY**

lakukan menggunakan perintah dibawah ini
---

$ git add README.md
$ git commit -m "desicription"
$ git push -u origin main
---

lebih lengkapnya lihat foto

![scs5](pict_practice/scs5.png)

![scs6]pict_practice/scs6.jpg