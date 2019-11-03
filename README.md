Download aplikasi git. lalu buka aplikasi tersebut
Menambahkan Global Config.Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email.
Buka direktory aktif, misal: d:\labs_pemrograman1.
klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash command 
Buat direktory project praktikum pertama dengan nama latihan1
Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory) • direktory aktif menjadi: d:\labs_pemrograman1\latihan1
![](Screenshot/1.png)
Jalankan perintah git init, untuk membuat repository local.
Disini kita akan coba buat satu file bernama README.md (text file)
![](Screenshot/2.png)
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
![](Screenshot/3.png)
Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
![](Screenshot/4.png)
Server reopsitory yang akan kita gunakan adalah http://github.com 
Pada laman github, klik tombol start a project, atau dari menu (icon +) klik New Repository.
![](Screenshot/5.png)
Isi nama repositorynya, misal: labpy1. lalu klik tombol Create repository.
![](Screenshot/6.png)
Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]
![](Screenshot/7.png)
Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
![](Screenshot/8.png)
Buka laman github.com, arahkan pada repositorinya.Maka perubahan akan terlihat pada laman tersebut.
![](Screenshot/9.png)
Untuk melakukan cloning, gunakan perintah git clone [url]
![](Screenshot/10.png)

