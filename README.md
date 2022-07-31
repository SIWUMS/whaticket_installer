Instalação de servidores VPS

Atualizando a VPS
```bash
sudo apt-get update -y && sudo apt-get upgrade -y
```

Criando uma imagem do instalador do WhaTicket na pasta raiz
```bash
cd ~
sudo apt install git -y && sudo git clone https://github.com/SIWUMS/whaticket_installer.git
sudo chmod +x ./whaticket_installer/whaticket
cd ./whaticket_installer
sudo ./whaticket
```
