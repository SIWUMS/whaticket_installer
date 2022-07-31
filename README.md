Instalação de servidores VPS

Criando uma imagem do instalador do WhaTicket na pasta raiz
```bash
sudo apt-get update -y && sudo apt-get upgrade -y
```bash
cd ~
sudo apt-get update -y && sudo apt-get upgrade -y && apt install git -y && sudo git clone https://github.com/SIWUMS/whaticket_installer.git
sudo chmod +x ./whaticket_installer/whaticket
cd ./whaticket_installer
sudo ./whaticket
```
