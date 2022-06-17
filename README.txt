CARA MENGINSTAL:

1. pkg-update && pkg-upgrade 
2. apt-get install proot-distro
3. proot-distro install debian
4. proot-distro login debian
5. apt-get update && apt-upgrade
6. apt install git build-essential libssl-dev zlib1g-dev yasm pkg-config libgmp-dev libpcap-dev libbz2-dev
7. git clone https://github.com/openwall/john
8. cd john/src
9. ./configure
10. make -s clean && make -sj4
