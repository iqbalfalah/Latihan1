# Latihan1
LANGKAH LANGKAH AWAL DALAM MENGGUNAKAN GITHUB

Membuat akun pada layanan github

![image](https://user-images.githubusercontent.com/46512186/51581023-16d10d80-1ef9-11e9-8926-a5c303a3e312.png)

untuk menggunakan git, dibutuhkan sebuah layanan. Layanan yang tersedia sangat banyak namun saya menggunakan github, tidak masalah kalau nanti misalnya mau pindah ke layanan lain seperti gitlab seperti yang saya lakukan sekarang, karena saya tetap menggunakan keduanya.
Setelah terbuat akun-nya, login dengan akun baru (kalau langsung diarahkan ke halaman utama), setelah itu pada pojok kanan atas terdapat tombol “+”, klik button tersebut dan pilih “new repository”.

Membuat Repositori online

![image](https://user-images.githubusercontent.com/46512186/51581053-2f412800-1ef9-11e9-9514-044eac84c671.png)

![image](https://user-images.githubusercontent.com/46512186/51581061-3700cc80-1ef9-11e9-9eec-2fed4fb3172f.png)


Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repositori.
Untuk mengisi, ada beberapa hal yang perlu di perhatikan :
•	Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.
•	Description : deskripsi repository (bisa kisah project dan siapa yang terlibat)
•	Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)
•	Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.

Setelah di isi sesuai dengan keinginan, klik saja tombol “create repository”, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.
Mengupload folder(repositori lokal)

![image](https://user-images.githubusercontent.com/46512186/51581077-43852500-1ef9-11e9-8a51-e4d7c955767b.png)


    Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, untuk Windows bisa menggunakan cmder yang sempat saya tulis disini untuk memudahkan proses penggunaan git, sedangkan untuk pengguna linux bisa menginstall dengan menggunakan perintah “sudo apt-get install git” jika menggunakan OSX install dengan brew, jika sudah file siap di upload ke repository online.
    jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line, atau jika belum terbiasa di command line (nanti belajar command line) buka saja folder tersebut menggunakan file exploler dan klik kanan “open terminal/cmder here”. Ada beberapa perintah dasar yang akan digunakan, perintah ini sudah tersedia kok saat membuat repo tadi (lihat gambar atas) 
git init 
git add . 
git commit -m "first commit" 
git remote add origin https://github.com/iqbalfalah/Latihan1.git 
git push -u origin master
 
Setelah Mengupload tugas hasilnya akan jadi seperti di bawah ini 

![image](https://user-images.githubusercontent.com/46512186/51581106-5992e580-1ef9-11e9-9872-6fe3ed997e3f.png)


Keterangan perintah diatas seperti ini :
git init
untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali
git add “.” atau nama file
untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload kalian bisa menggunakan perintah tersebut. Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan “nama file” untuk memberikan status commit. Ini adalah contohnya apabila ingin menggunakan “git add” :
// mengupload keseluruhan file pada repo (hanya digunakan saat upload pertama saja)
git add .
// mengupload file sesuai dengan nama file
git add index.html
// mengupload file pada dalam folder
git add pages/index.html
git commit -m “isi commit”
untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh).
git remote add origin “link repo online”
untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format “.git”, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.

git push origin “nama branch”
Perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online.
Setelah melakukan semua perintah silahkan cek di github, apakah file yg di upload sudah masuk atau tidak? jika iya maka anda berhasil mengelola git untuk tahap awal

Bentuk kode yang sudah dimasukan ke GitBash


![image](https://user-images.githubusercontent.com/46512186/51581219-b68e9b80-1ef9-11e9-82b8-24116f8e2514.png)


![image](https://user-images.githubusercontent.com/46512186/51581220-ba222280-1ef9-11e9-9175-580729858041.png)






