# install badvpn
wget -O /usr/bin/badvpn-udpgw "http://kimnoon.configinter.net/ssh/script/badvpn-udpgw"wget -O /usr/bin/badvpn-udpgw "http://kimnoon.configinter.net/ssh/script/badvpn-udpgw"
sed -i '$ i\screen -AmdS badvpn badvpn-udpgw --listen-addr 127.0.0.1:7300' /etc/rc.local
chmod +x /usr/bin/badvpn-udpgw
screen -AmdS badvpn badvpn-udpgw --listen-addr 127.0.0.1:7300
