# OpenVPN-Linux-Build

***Building latest OpenVPN v2.5.4 on Linux***
```
apt update -y -v
apt upgrade -y -v
apt install build-essential libssl-dev liblzo2-dev libpam0g-dev zlib1g zlib1g-dev
wget https://swupdate.openvpn.org/community/releases/openvpn-2.5.4.tar.gz
tar -xvf openvpn-2.5.4.tar.gz
cd openvpn-2.5.4
./configure
make
make install
```
