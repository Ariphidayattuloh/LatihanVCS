# LatihanVCS
Nama : Arip Hidayattuloh
Nim  : 312010244
Kelas: TI.20.B.1
Tugas: Membuat satu repository LatihanVCS dan Buat file README.md
Dosen: Agung Nugroho S.Kom, M.kom

Instalasi Git

• Download Git, buka website resminya Git (git-scm.com).

• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.


![pic 2 1](https://user-images.githubusercontent.com/72840534/96367580-f63ef180-1178-11eb-96b6-5dda04c64fdd.jpg)

![pic 3](https://user-images.githubusercontent.com/72840534/96367595-08209480-1179-11eb-9fdb-cf8707a157de.jpg)


Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah

git --version

![pic 4](https://user-images.githubusercontent.com/72840534/96367601-0d7ddf00-1179-11eb-8dd6-ef2dee401a8c.jpg)

Menambahkan Global Config

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email

• konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

• apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

• Config Global Repository

$ git config --global user. name “nama_user”

$ git config --global user. email “nama_user”

![pic 5 1](https://user-images.githubusercontent.com/72840534/96367605-1373c000-1179-11eb-9e18-bb2f1afc882b.jpg)


Membuat Reposiory Local

• Buka direktory aktif, misal: e:\labs_pemrograman1 (buka menggunakan Windows Explorer)

• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad

• Buat direktory project praktikum pertama dengan nama Latihan-VCS

$ mkdir Latihan-VCS

$ cd Latihan-VCS

![pic 6](https://user-images.githubusercontent.com/72840534/96367610-1b336480-1179-11eb-9d37-7be4625bdcad.jpg)

• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)

• direktory aktif menjadi: e:\labs_pemrograman1\Latihan-VCS

Membuat Reposiory Local

• Jalankan perintah git init, untuk membuat repository local.

$ git init

![pic 7](https://user-images.githubusercontent.com/72840534/96367612-1e2e5500-1179-11eb-89f5-fd2f94acffea.jpg)


• Repository baru berhasil di inisialisasi, dengan terbentuknya satu Direktori hidden dengan nama .git

![pic 8](https://user-images.githubusercontent.com/72840534/96367614-21294580-1179-11eb-97a4-516a82407145.jpg)

• Pada direktori tersebut, semua perubahan pada working directory akan disimpan.

Menambahkan File baru pada repository

• Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)

• disini kita akan coba buat satu file bernama README.md (text file)

$ echo “# Latihan-VCS” >> README. md

![echo1](https://user-images.githubusercontent.com/72840534/96368045-af9ec680-117b-11eb-81b6-6b4a8f7e4f1d.png)

• File README.md berhasil dibuat.

![readme](https://user-images.githubusercontent.com/72840534/96368179-b11cbe80-117c-11eb-8ba4-2de88299c570.jpg)

Menambahkan File baru pada repository

• Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

$ git add README. md

• File README.md berhasil ditambahkan

![readm berhasil](https://user-images.githubusercontent.com/72840534/96368438-060d0480-117e-11eb-97d7-59da7d7d23bb.jpg)


Commit (Menyimpan perubahan ke database)

• Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”

$ git commit -m “Bahasa Pemrograman Repository Lokal LatihanVCS"

![readm COMMIT](https://user-images.githubusercontent.com/72840534/96368607-d27eaa00-117e-11eb-973b-1148d683b9be.jpg)


• Perubahan berhasil disimpan

![BUKA FILE](https://user-images.githubusercontent.com/72840534/96368701-88e28f00-117f-11eb-811f-e05fa64d404b.jpg)

Membuat repository server

• Server reopsitory yang akan kita gunakan adalah http://github.com

• Anda harus membuat akun terlebih dahulu.

• Pada laman github, klik tombol start a project, atau

• Dari menu (icon +) klik New Repository

(Gambar)
Membuat repository server

• Isi nama repositorynya, misal: LatihanVCS.

(Gambar)
• lalu klik tombol Create repository
(Gambar)
Menambahkan Remote Repository

• Remote Repository merupakan repository server yang akan

digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.

Alamat url kita

(Gambar)

• Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

$ git remote add origin https://github.com/ariphidayattuloh/LatihanVCS.git

(Gambar)
Push (Mengirim perubahan ke server)

• Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.

$ git push -u origin master

• Perintah ini akan meminta memasukkan username dan password pada akun github.com

(Gambar)

Melihat hasilnya pada server repository

• Buka laman github.com, arahkan pada repositorinya.

• Maka perubahan akan terlihat pada laman tersebut.

(Gambar)
Clone Repository

• Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).

• Untuk melakukan cloning, gunakan perintah git clone [url]

$ git clone https://github.com/ariphidayattuloh/LatihanVCS.git
(Gambar)

Kegunaan file README.md

• Apabila kita menggunakan github, untuk memberikan penjelasan awal pada project yang kita buat, maka dapat menggunakan sebuah file yang bernama README.md

• Pada file tersebut kita dapat membuat dokumentasi awal dari setiap project yang kita buat untuk memberikan penjelasan atau sekedar cara penggunaan dari aplikasi yang kita kembangkan.

• Penulisan file README.md berbasis teks, dan untuk pemformatannya menggunakan Markdown format.

• untuk lebih jelasnya, dapat anda gunakan cara penggunaan markdown

TERIMA KASIH😊



