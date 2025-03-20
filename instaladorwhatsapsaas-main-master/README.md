ATUALIZANDO MAQUINA 

```bash


sudo apt -y update && apt -y upgrade

```


FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/barbosajudson/atualiza.git && sudo chmod -R 777 atualiza/instaladorwhatsapsaas-main-master && cd atualiza/instaladorwhatsapsaas-main-master && sudo ./install_primaria

```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./instaladorwhatsapsaas-main && sudo ./install_instancia
```

