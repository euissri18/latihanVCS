# latihanVCS
Euis Sri Mulyani<br>
312010457<br>
TI.20.A.1<br>


### INSTALASI GIT
* Download *Git*, buka website resminya Git (git-scm.com)
![GitScm](https://user-images.githubusercontent.com/72909071/97097517-ec028300-16a3-11eb-96ee-68eb234e8a8e.png)
* Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
![installing](https://user-images.githubusercontent.com/72909071/97097525-f3c22780-16a3-11eb-9e7a-fa2a18619f42.png)
* Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka *CMD* atau *PowerShell*, kemudian ketik perintah<br>
"git --version"

![version](https://user-images.githubusercontent.com/72909071/97097528-f6bd1800-16a3-11eb-9db3-43f6d777b188.png)

### Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi ``user.name dan user.email``
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah `git commit`

* Config Global Repository

`$ git config --global user.name “nama_user"`

![username](https://user-images.githubusercontent.com/72909071/97097530-f91f7200-16a3-11eb-9401-d266a9ae6e00.png)


`$ git config --global user.email “nama_user”`

![user](https://user-images.githubusercontent.com/72909071/97097532-fae93580-16a3-11eb-8804-4330c05938f5.png)

### Perintah Dasar Git

* `git init`, perintah untuk membuat repository local
* `git add`, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
* `git commit`, perintah untuk menyimpan perubahan kedalam database git.
* `git push -u origin master`, perintah untuk mengirim perubahan pada repository local menuju server repository.
* `git clone [url]`, perintah untuk membuat working directory yang diambil dari repositry sever.
* `git remote add origin [url]`, perintah untuk menambahkan remote server/reopsitory server pada local repositry ``(working directory)``
* `git pull`, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository


### Membuat Reposiory Local

* Buka direktory aktif, misal: *d:\labs_pemrograman1* (buka menggunakan Windows Explorer)
* klik kanan pada direktory aktif tersebut, dan pilih menu *Git Bash*, sehingga muncul git bash commad
* Buat direktory project praktikum pertama dengan nama *latihan1*
``$ mkdir latihan1
$ cd latihan1``
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah *cd* ``(change directory)``
* direktory aktif menjadi: **d:\labs_pemrograman1\latihan1


### Membuat Reposiory Local

* Jalankan perintah *git init*, untuk membuat repository local.
`$ git init`
* Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .*git*
* Pada direktori tersebut, semua perubahan pada `working directory` akan disimpan.


### Menambahkan File baru pada repository

* Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
* disini kita akan coba buat satu file bernama README.md (text file)
`$ echo “# Latihan 1” >> README.md`
* File *README.md* berhasil dibuat.
