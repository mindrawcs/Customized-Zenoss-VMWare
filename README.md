PETUNJUK INSTALASI

1. download zenoss_core-4.2.5-2108-x86_64.vmware.zip di http://sourceforge.net/projects/zenoss/

2. Unzip file tersebut ke folder yang diinginkan

3. Download dan Install VMware Player 12 https://www.vmware.com/products/player/playerpro-evaluation 

4. Browse fie .vmdk di folder yang telah di unzip
5.setelah zenoss virtual appliance dibuka maka akan ada loading CentOs dan inisialiasi Zenoss
6. Setelah Zenoss management Console Muncul maka masukkan IP address yang tertera di Web Browser

KONFIGURASI
1.Setelah memasukkan IP address yang tertera maka web akan direct ke halaman Getting Started.
2. Setelah itu Zenoss akan meminta password untuk Admin, Username dan password serta email.
3. Laman berikutnya adalah Pencarian Device untuk Monitoring.
4.Terakhir Zenoss akan memasuki Dashboard.

PLUGINS
Plugins di Zenoss salah satunya berupa Zenpacks.Zenpacks dapat dibuat sendiri ataupun mengunduhnya dari wiki.zenoss.org. File dari zenpacks bmempunyai ekstensi .egg.

Security Plugins
Security Plugins yang digunakan adalah  	ZenPacks.zenoss.Microsoft.Windows . Plugins ini sudah built ini didalam Zenoss 4.2.5. Zenpacks ini mengatur authentication pada Kerberos. Kita juga bisa memilih HTTPS Protocol untuk enkripsi user name dan password.
Accounting Plugins
Plugins Untuk accounting yang kami pilih adalah Zenpacks FreeRADIUS. Zenpack ini memunculkan grafik MEtrik total Access, Authentication dan Accounting. http://wiki.zenoss.org/ZenPack:FreeRADIUS

INSTALASI ZENPACKS
1.Instalasi Zenpacks dilakukan dengan membuka Dashboard di Zenoss Web UI dan memilih Tab Advanced.
2. Di Tab Settings pilih Zenpacks
3. di Sebelah Loaded Zenpacks klik Symbol Gear dan pilih Install Zenpacks
4. Pilih file Zenpacks(ekstensi .egg) yang telah didownload sebelumnya

