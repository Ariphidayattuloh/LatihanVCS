# LatihanVCS
Nama : Arip Hidayattuloh
Nim  : 312010244
Kelas: TI.20.B.1
Tugas: Membuat satu repository LatihanVCS dan Buat file README.md
Dosen: Agung Nugroho S.Kom, M.kom

Instalasi Git

• Download Git, buka website resminya Git (git-scm.com).

• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

![Pict-1](https://user-images.githubusercontent.com/72840534/96367201-87f92f80-1176-11eb-9615-b8d519213e11.jpg)

Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah

git --version

(Gambar)

Menambahkan Global Config

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email

• konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.

• apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

• Config Global Repository

$ git config --global user. name “nama_user”

$ git config --global user. email “nama_user”

(Gambar)

Membuat Reposiory Local

• Buka direktory aktif, misal: e:\labs_pemrograman1 (buka menggunakan Windows Explorer)

• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad

• Buat direktory project praktikum pertama dengan nama Latihan-VCS

$ mkdir Latihan-VCS

$ cd Latihan-VCS

(Gambar)
• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)

• direktory aktif menjadi: e:\labs_pemrograman1\Latihan-VCS

Membuat Reposiory Local

• Jalankan perintah git init, untuk membuat repository local.

$ git init

(Gambar)

• Repository baru berhasil di inisialisasi, dengan terbentuknya satu Direktori hidden dengan nama .git
(Gambar)
• Pada direktori tersebut, semua perubahan pada working directory akan disimpan.
(Gambar)
Menambahkan File baru pada repository

• Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)

• disini kita akan coba buat satu file bernama README.md (text file)

$ echo “# Latihan-VCS” >> README. md

(Gambar)
• File README.md berhasil dibuat.
(Gambar)
Menambahkan File baru pada repository

• Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

$ git add README. md

• File README.md berhasil ditambahkan
(Gambar)

Commit (Menyimpan perubahan ke database)

• Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”

$ git commit -m “Bahasa Pemrograman Repository Lokal LatihanVCS"

(Gambar)
• Perubahan berhasil disimpan
(Gambar)
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



