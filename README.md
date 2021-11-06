# OpenVPN-Linux-Build

***Building latest OpenVPN v2.5.4 on Linux***
```
apt update
apt upgrade
apt install build-essential
wget https://swupdate.openvpn.org/community/releases/openvpn-2.5.4.tar.gz
tar -xvf openvpn-2.5.4.tar.gz
cd openvpn-2.5.4
./configure
make
make install
```
