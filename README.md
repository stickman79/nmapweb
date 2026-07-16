aviso baixe gcc C++/C

# 🐧 No Ubuntu, Debian, Linux Mint e derivados:

sudo apt update
sudo apt install build-essential
 
# 🔴 No Fedora, Red Hat (RHEL) e CentOS:

sudo dnf groupinstall "Development Tools"

# 🔵 No Arch Linux e Manjaro:

sudo pacman -S base-devel

# para ver se deu certo use: 

gcc --version

# aviso! se voce usa windows melhor baixar algum subsistema linux!

para rodar o codigo baixe o arquivo

depois de gcc ia.c -o ia

depois execute ./ia

pronto voce recebera o link do site!

ou clone o repositorio:

git clone https://github.com/stickman79/nmapweb
cd nmapweb
gcc ia.c -o ia
./ia

