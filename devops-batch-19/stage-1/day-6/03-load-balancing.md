# Load Balancing

Load balancing adalah praktik untuk mendistribusikan lalu lintas jaringan atau beban kerja komputasi di antara beberapa sumber daya komputer atau server. Tujuannya adalah untuk mencegah satu sumber daya menjadi terlalu terbebani sementara yang lain memiliki kapasitas kosong yang tidak terpakai. Untuk membuat konfigurasi load balancing, tools yang diperlukan adalah 2 server yang sudah terintal aplikasi dan nginx. Jika toolsya sudah lengkap, pertama buat konfigurasinya. Masuk ke folder nginx dan buat folder baru, kemudian masuk ke folder baru tersebut dan buat file baru dengan ektensi `.conf`

    cd /etc/nginx
    sudo mkdir reverse-proxy
    cd reverse-proxy
    sudo touch rf.conf

Masukkan kode berikut ke dalam file yang baru dibuat

    upstream beta {
            server 192.168.43.130:3000;
            server 192.168.43.131:3000;
    }
    
    
    server {
        server_name beta.xyz;
    
        location / {
                 proxy_pass http://beta;
        }
    }

> Pada bagian upstream dapat diganti dengan nama domain yang akan digunakan.
>
> Pada bagian server, masukan IP dari server yang sudah terpasang aplikasi dan diikuti dengan port aplikasi.
> 
> Bagian proxy_pass, samakan dengan nama upstream.

![gambar konfigurasi]()

Jalankan nginx test untuk mengetahui error syntax. Jika tidak ada restart nginx

![gambar cek syntax]()

Jalankan aplikasi yang ada di server dan panggil domain yang dikonfigurasi.

![gambar run app]()

![gambar app web]()

Untuk mengetahui apakah konfigurasi load balancing yang dilakukan benar-benar berhasil, matikan salah satu aplikasi server kemudian reload domain konfigurasinya. Jika konfigurasi berhasil maka aplikasinya masih berjalan.
