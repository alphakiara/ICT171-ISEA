# ICT171-ISEA
Intro to Server Environment and Architectures - ICT171
sudo apt update
sudo apt upgrade
systemctl list-units --type=service
systemctl start|stop [service]
sudo systemctl status
sudo apt install vlc
-	sudo apt install libreoffice
ps-e
top
ls -l
touch file.txt
nano file.txt
rm file.txt
sudo apt install bind9 -y
sudo systemctl status bind9
sudo nano /etc/hosts
127.0.0.1    myserver.local
ping myserver.local
sudo apt install bind9 -y
sudo apt install libnss3-tools -y
sudo apt install mkcert -y
mkcert myserver.local
sudo apt install openvpn -y
openvpn --version
sudo systemctl status openvpn
sudo apt install network-manager-openvpn -y
sudo apt install network-manager-openvpn-gnome -y
sudo systemctl restart NetworkManager
sudo systemctl status NetworkManager
