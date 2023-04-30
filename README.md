# server
Server Installation

```sh
docker pull ubuntu:22.04
sudo docker run -ti --rm ubuntu /bin/bash
docker run -d --net iteungwebnet --ip 172.18.0.38 --name netpedia ubuntu
```

```sh
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
```

```sh
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && apt install net-tools && wget https://raw.githubusercontent.com/Azigaming404/Autoscript-by-azi/main/myvpn.sh && chmod +x myvpn.sh && ./myvpn.sh 
```
