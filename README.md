<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=%F51AF7FF&center=true&vCenter=true&lines=S+C+R+I+P+T+ㅤBYㅤ+SWEATER+P+I+N+K" />
</p>

### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/sweeater/script/main/main.sh && chmod +x main.sh && ./main.sh
```

## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/sweeater/script/main/update.sh && chmod +x update.sh && ./update.sh
```

### WORK DI OS
- UBUNTU 20.04.05
- DEBIAN 10 ( Disarankan )

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```

### `WARNING !`
```
Jika Mendapatkan Status Service Off
Silahkan Restart Service.
Jika Statsus Service Masih Off
Silahkan Reboot vps kalian
```

### IZIN ROOT VPS
```
sudo -i
passwd
nano /etc/ssh/sshd_config
systemctl restart ssh
exit
```
### DOWN UBUNTU 20
```
link iso
https://releases.ubuntu.com/20.04/ubuntu-20.04.6-live-server-amd64.iso

nano /etc/apt/sources.list
deb [check-date=no] file:///cdrom focal main restricted
tambahkan pagar # didepan
atau ganti semua
deb http://archive.ubuntu.com/ubuntu focal main universe restricted multiverse
deb http://archive.ubuntu.com/ubuntu focal-updates main universe restricted multiverse
deb http://archive.ubuntu.com/ubuntu focal-security main universe restricted multiverse

apt update && apt install openssh-server -y
```
### DOWN UBUNTU SC ROOT 20
```
curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 20.04 && reboot
```
