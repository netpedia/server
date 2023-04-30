# server
Server Installation

```sh
docker run -d --net iteungwebnet --ip 172.18.0.38 --name netpedia -e TZ=Asia/Jakarta ubuntu/nginx:1.18-20.04_beta
docker exec -it netpedia /bin/bash
```

```sh
sudo su
apt update && apt upgrade -y && apt dist-upgrade -y && update-grub && reboot
dpkg-reconfigure tzdata
apt install tmux
```

tmux : https://awangga.github.io/nopanel/tmux/

```sh
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt install -y bzip2 gzip coreutils screen curl net-tools
wget https://raw.githubusercontent.com/Azigaming404/Autoscript-by-azi/main/myvpn.sh && chmod +x myvpn.sh && ./myvpn.sh 
```
