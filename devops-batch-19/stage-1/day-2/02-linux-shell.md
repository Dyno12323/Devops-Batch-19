# Linux Shell

Linux shell merupakan antarmuka pengguna yang menyediakan cara untuk berinteraksi dengan sistem operasi dan mengeksekusi perintah. Shell adalah program yang menyediakan lingkungan atau wadah (interface) tempat Anda dapat memasukkan perintah, menjalankan skrip, mengelola file, dan berinteraksi dengan sistem operasi. Salah satu shell yang paling umum digunakan adalah bash (Bourne Again Shell). Berikut beberapa command yang sering digunakan 

#### sudo

Perintah "sudo" digunakan untuk memberikan hak akses superuser atau administrator kepada pengguna untuk menjalankan perintah dengan hak istimewa. Istilah "sudo" sendiri adalah singkatan dari "superuser do". Perintah "sudo" memungkinkan pengguna untuk menjalankan perintah dengan hak istimewa hanya saat diperlukan, memberikan kontrol akses yang lebih baik pada sistem Linux dan mengurangi risiko perintah yang berpotensi berbahaya dilakukan secara tidak sengaja.

#### mkdir

Perintah `mkdir` digunakan untuk membuat direktori atau folder baru di dalam sistem. `mkdir` merupakan singkatan dari "make directory". Untuk membuat direktori baru, cukup jalankan perintah `mkdir` diikuti dengan nama direktori yang ingin dibuat.

    mkdir folder-baru

Perintah `mkdir` bisa juga digunakan untuk membuat beberapa direktori sekaligus dengan memberikan beberapa nama direktori setelah perintah mkdir.

    mkdir folder-1 folder-2 folder-3

#### ls

Perintah `ls` digunakan untuk menampilkan daftar file dan direktori dalam direktori kerja saat ini. Ini membantu pengguna untuk melihat konten dari direktori di mana perintah tersebut dijalankan.

    ls

Perintah `ls` dapat diikuti dengan perinth `-l` untuk menampilkan informasi secara rinci, seperti izin akses, pemilik, ukuran, dan tanggal modifikasi.

    ls -l

Selain menambahkan perintah `-l`, perintah `ls` bisa diikuti dengan perintah `-a` yang akan menampilkan semua file, termasuk file file tersembunyi.

    ls -a

Perintah yang ada dibelakang perintah `ls` dapat dikombinasikan menjadi `-la` untuk melihat informasi dan menampilkan semua file.

    ls -la

#### cd

Perintah `cd` digunakan untuk berpindah dari satu direktori ke direktori lain dalam suatu sistem file. Untuk pindah ke direktori tertentu, cukup menjalankan perintah `cd` diikuti dengan nama direktori yang ingin dituju.

    cd file-1

Untuk kembali ke direktori sebelumnya, bisa menjalankan perintah `cd` diikuti perintah `../`.

    cd ../

#### touch

Perintah `touch` digunakan untuk membuat file kosong dalam suatu direktori. Untuk membuat file kosong baru, gunakan perintah `touch` diikuti dengan nama file yang ingin dibuat.

    touch file-1.html

Perintah `touch` juga bisa digunakan untuk membuat beberapa file sekaligus dengan memberikan beberapa nama file setelah perintah `touch`.

    touch file-1.html file-2.txt file-3.md

#### cp

Perintah `cp` digunakan untuk menyalin file atau direktori dari satu lokasi ke lokasi lain dalam suatu sistem. Untuk menyalin file dari lokasi asal ke lokasi tujuan, gunakan perintah `cp` diikuti dengan nama file dan lokasi tujuan.

    cp file-yang-ingin-dicopy.txt /lokasi/tujuan/

Perintah `cp` juga bisa digunakan untuk menyalin beberapa file ke lokasi tertentu dengan menyebutkan beberapa nama file setelah perintah `cp` dan menentukan lokasi tujuan.

    cp file-1.html file-2.txt file-3.md /lokasi/tujuan/

#### mv

Perintah `mv` digunakan untuk memindahkan move file atau direktori dari satu lokasi ke lokasi lain dalam suatu sistem. Selain memindahkan, perintah ini juga dapat digunakan untuk mengubah nama file atau direktori. Untuk **memindahkan** file dari lokasi asal ke lokasi tujuan, gunakan perintah `mv` diikuti dengan nama file dan lokasi tujuan.

    mv file-yang-ingin-dipindah.txt /lokasi/tujuan/

Untuk **merubah** nama file dapat menggunakan perintah `mv` diikuti dengan nama file lama dan nama file baru.

    mv nama-file-lama.html nama-file-baru.html

#### cat

Perintah `cat` digunakan untuk membaca, menggabungkan, dan menampilkan isi dari satu file. Untuk menampilkan isi dari satu file, cukup gunakan perintah `cat` diikuti dengan nama file.

    cat nama-file.txt

Perintah `cat` juga dapat menggabungkan beberapa file dan menyimpannya ke file baru.

    cat file-1.md file-2.md > file-baru.md

#### grep

Perintah `grep` digunakan untuk mencari kata dalam satu atau beberapa file, kemudian menampilkannya. Untuk mencari kata dalam satu file, gunakan perintah `grep` diikuti dengan kata yang ingin dicari diikuti dengan nama file yang ingin diperiksa.

    grep "kata yang ingin dicari" nama-file.txt

#### chmod

Perintah `chmod` digunakan untuk mengubah izin akses dari file. Untuk mengubah izin akses, gunakan `chmod` diikuti dengan mode yang ingin diatur dan nama file yang ingin diubah izinnya.

    chmod u+rwx nama_file.txt

> u+rwx berarti menambahkan hak akses untuk pemilik  dengan memberikan izin read, write, dan execute.

#### chown

Perintah `chown` digunakan untuk mengubah pemilik dari suatu file. Untuk mengubah pemilik dari sebuah file, gunakan perintah `chown` diikuti dengan nama pengguna dan nama file yang ingin diubah pemiliknya.

    chown nama-pengguna nama-file.txt

#### history

Perintah `history` digunakan untuk menampilkan daftar perintah yang telah dieksekusi oleh pengguna dalam sesi terminal tersebut. 

#### ping

Perintah `ping` digunakan untuk menguji koneksi jaringan antara dua perangkat dengan mengirim data ke tujuan yang ditentukan dan menerima respons balik. Untuk menggunakannya, jalankan perintah `ping` diikuti dengan alamat IP atau nama domain  tujuan yang ingin di uji koneksinya.

    ping www.google.com

#### wget

Perintah `wget` pada sistem Linux digunakan untuk mengunduh file dari internet.

#### adduser

Perintah `adduser` digunakan untuk menambahkan pengguna baru ke dalam sistem. Untuk menambahkan pengguna baru, jalankan perintah `adduser` diikuti dengan nama pengguna yang ingin di tambahkan.

    adduser nama-pengguna-baru

#### usermod

Perintah `usermod` digunakan untuk mengubah pengaturan dari pengguna yang sudah ada dalam sistem. Untuk menambahkan pengguna ke grup tertentu, gunakan opsi -aG diikuti dengan nama grup yang diinginkan.

    sudo usermod -aG nama-grup nama-pengguna

#### sudo su

Perintah `sudo su` digunakan untuk beralih dari user yang digunakan saait ini ke superuser/root. Ini memberikan akses administrator yang luas untuk melakukan tugas-tugas administratif di sistem.

#### rm

Perintah `rm` digunakan untuk menghapus file atau direktori. Untuk menghapus file, jalankan perintah `rm` diikuti dengan nama file yang ingin di hapus.

    rm nama-file.txt

