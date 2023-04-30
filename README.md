# server
Server Installation

```sh
docker run -d --net iteungwebnet --ip 172.18.0.38 --name netpedia -e TZ=Asia/Jakarta ubuntu/nginx:1.18-20.04_beta
docker exec -it netpedia /bin/bash
```

```sh
sudo apt-get update
sudo apt-get upgrade -y
sudo apt dist-upgrade -y
sudo update-grub
sudo reboot
sudo apt install tmux
```

```sh
sudo sysctl -w net.ipv6.conf.all.disable_ipv6=1
sudo sysctl -w net.ipv6.conf.default.disable_ipv6=1
apt update
sudo apt install -y bzip2 gzip coreutils screen curl
sudo apt install net-tools
wget https://raw.githubusercontent.com/Azigaming404/Autoscript-by-azi/main/myvpn.sh
chmod +x myvpn.sh
sudo ./myvpn.sh 
```
