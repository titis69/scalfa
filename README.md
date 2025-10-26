

### SETING ROOT DULU
### 
kemudian ubahlah PermitRootLogin without-password menjadi   PermitRootLogin yes
```
nano /etc/ssh/sshd_config
```

### hilangkan tanda pagar pada PasswordAuthentication yes
```
nano /etc/ssh/ssh_config
```
### BUAT PASSWORD USER ketik passwd root  = passwd root

### restart ssh
```
service ssh reload
```



### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/titis69/scalfa/main/start.sh && chmod +x start.sh && ./start.sh
```

## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/titis69/scalfa/main/update.sh && chmod +x update.sh && ./update.sh
```
### INSTALL SCRIPT X
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/titis69/scalfa/main/startX.sh && chmod +x startX.sh && ./startX.sh
```

### SUPPORT OS LINUX
- UBUNTU 20.04.05
- DEBIAN 10

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
### INFO PORT
```
- PORT WEBSOCKET » 80
- PORT TLS / SSL » 443
- PORT HANCED WS » 80 » 8080
- PORT NOOBZVPN  » 2082 » 8880  
```
### `WARNING !`
```
Jika Mendapatkan Status Service Off
Silahkan Restart Service.
Jika Statsus Service Masih Off
Silahkan Reboot vps kalian
```


- Langkah 1: 
Membuat Bot di Telegram
Buka Telegram dan Cari BotFather:

Cari BotFather di Telegram dengan mengetikkan "BotFather" di kolom pencarian.
Pilih BotFather (akun resmi dengan tanda centang biru).
Membuat Bot Baru:
Kirim pesan /start ke BotFather untuk memulai.
Kirim pesan /newbot untuk membuat bot baru.
Ikuti instruksi untuk memberikan nama dan username untuk bot Anda.
Setelah selesai, BotFather akan memberikan token API bot. Simpan token ini karena akan digunakan dalam skrip Anda.


- Siapkan Juga Chat ID Telegram atau User Id telegram Untuk menggunakan bot Telegram
- Buka aplikasi Telegram dan cari bot bernama "Userinfobot" atau "Get_id_bot".
- Klik "Start" untuk memulai bot.
Bot akan secara otomatis mengirimkan pesan berisi chat ID kamu.
