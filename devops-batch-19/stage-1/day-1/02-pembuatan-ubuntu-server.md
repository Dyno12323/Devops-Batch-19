# Instalasi Ubuntu Server

Sebelum instalasi ubuntu server, siapkan toolsnya dulu. Tools yang digunakan ialah VMWare Workstation dan Ubuntu Server. Bila toolsnya sudah tersedia, berikut langkahnya.

- Buka VMWare dan pilih Create a New Virtual Machine

![gambar create new vm](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-create-new-vm.png)

- Pilih use ISO image, kemudian browse dan cari file ISO ubuntu server yang sudah didownload

![gambar use iso image](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-use-iso-image.png)

- Pilih OS yang akan di install yaitu linux server 64-bit

![gambar pilih os](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-pilih-os.png)

- Tentukan nama dan lokasi penyimpanan Virtual Machine

![gambar namai server](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-namai-server.png)

- Atur disk size yang ingin digunakan

![gambar atur disk](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-atur-disk.png)

- Atur memory, processor, dan network adapter virtual machine yang akan dibuat

![gambar atur vm](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-atur-vm.png)

- Atur network connection menjadi bridged. Nanti akan digunakan untuk mengatur ip statis

![gambar network connection](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-network-connection.png)

- Setelah selesai akan dikembalikan ke halaman rangkuman pembuatan virtual machine. Pilih finish untuk melanjutkan instalasi.

![gambar rangkuman vm](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-rangkuman-vm.png)

- Pilih bahasa yang digunakan untuk melanjutkan instalasi

![gambar pilih bahasa](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-pilih-bahasa.png)

- Muncul pilihan untuk update installer, bisa pilih continue without updating

![gambar update instaler](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-update-instaler.png)

- Muncul pilihan untuk layot keybord, pilih english

![gambar layout keybord](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-layot-keybord.png)

- Ubah pengaturan network connection menjadi statis

![gambar setting ip](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-setting-ip.png)

![gambar setting ip 2](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-setting-ip2.png)

- Setelah ip diatur menjadi statis pilih done untuk melanjutkan instalasi

![gambar ip statis lanjut](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-ipstatis-lanjut.png)

- Configure proxy bisa dibiarkan kosong. Pilih done untuk melanjutkan

![gambar configur proxy](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-configur-proxy.png)

- Atur disk partition

![gambar disk partition](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-atur-disk-partition.png)

![gambar disk partition2](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-disk-partition2.png)

- Mengatur username dan pasword yang digunakan untuk login

![gambar mengatur profil](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-mengatur-profil.png)

- Install ssh untuk server. SSH digunakan untuk meremote server.

![gambar setup ssh](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-setup-ssh.png)

- Tunggu hingga proses selesai

![gambar instal](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-instal.png)

- Proses install sudah selesai

![gambar linux sever](https://github.com/Dyno12323/devops-batch-19/blob/master/devops-batch-19/stage-1/day-1/images/02-pembuatan-server/vm-linux-server.png)
