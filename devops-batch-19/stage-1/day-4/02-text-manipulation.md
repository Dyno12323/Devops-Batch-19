# Text Manipulation

Manipulasi teks merupakan suatu kegiatan mengubah atau mengolah teks pada suatu file. Beberapa perintah yang biasa digunakan untuk memanipulasi teks

### `cat`

Perintah `cat` dapat digunakan untuk membuat file baru, menambahkan kata atau perintah kedalam file, ataupun menggabungkan isi file.

#### Membuat file baru menggunakan perintah `cat`

Perintah `cat` dapat digunakan untuk membuat file baru. Jalankan perintah `cat` diikuti dengan redirection `>` untuk membuat file baru.

    cat > file-baru.txt

Setelah menjalankan perintah tersebut, maka akan masuk ke mode input di mana pengguna dapat mengetikkan teks yang diinginkan ke dalam file tersebut. Setelah selesai, tekan Ctrl + D untuk menyimpan, dan file baru dengan nama file-baru.txt akan dibuat didalam direktori yang sedang aktif

#### Menggabungkan isi dari dua file menggunakan perintah `cat`

Untuk meggabungkan isi dari dua file kemudian menyimpannya menjadi file yang berbeda, jalankan perintah `cat` diikuti dengan file yang akan digabung dan tanda redirection `>`.

  cat file-1.txt file-2.txt > file-gabungan.txt

Perintah tersebut akan menggabungkan isi dari `file-1.txt` dan `file-2.txt`, dan menyimpannya dengan nama `file-gabungan`. *Nama file dapat diubah sesuai kebutuhan*

#### Mencari dan merubah kata tertentu dalam suatu file dengan perintah `sed`

Untuk mencari suatu kata pada file tertentu dan mengubah kata yang dicari menjadi kata yang lain, dapan menjalankan perintah :

    sed -i 's/Kata1/Kata2/g' nama-file 

Perintah `-i` menyatakan perubahan langsung diterapkan di file 

perintah `'s/` merupakan perintah untuk mengganti teks

Perintah `Kata1/` merupakan kata yang dicari dan ingin diganti

Perintah `Kata2/` merupakan kata yang ingin diterapkan

Perintah `g'` menyatakan perubahan diterapkan ke seluruh teks yang sesuai

Perintah `nama-file` menyatakan file yang akan dimodifikasi

#### Mencari kata dengan perintah `grep`

Untuk mencari kata atau kalimat dalam suatu file, gunakan perintah `grep` diikuti dengan kata atau kalimat yang ingin dicari dan file tempat kata ingin dicari.

    grep kata-yang-ingin-dicari nama-file.txt

#### Mengurutkan isi file dengan perintah `short`

Perintah `short` akan mengurutkan si dari suatu file secara alfabetis berdasarkan baris, dan menampilkan hasilnya ke dalam output terminal tanpa mengubah isi file. Untuk melakukannya, jalankan perintah `shot` diikuti dengan file yang ingin dilihat.

    short nama-file.txt 
