# CheckUser

*CheckUser* E um verificador de usuários.

# Modo de instalação


*RECOMENDO O USO DESSE ESTILO*
```
apt update -y && apt upgrade -y
```
```
wget https://raw.githubusercontent.com/WdsUtilidades/CheckUser/master/install.sh && chmod 777 install.sh && ./install.sh
```
### Ou Tudo Junto
```
apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/WdsUtilidades/CheckUser/master/install.sh && chmod 777 install.sh && ./install.sh
```
### Ou pode usar esses outros

# Modo de instalação
```
apt-get update && apt-get install git -y
```
```
python3 -m pip install git+https://github.com/WdsUtilidades/CheckUser.git
```

```
checkuser --create-service --config-port 5000 --start
```

### SE DER ERRO TENTE ATUALIZAR O PYTHON 
*Comandos*
```sudo apt install python3.7```
```sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1```
```sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.7 2```
*Ecolhe o Python3.7 nesse comando abaixo*
```sudo update-alternatives --config python3```
*verificar a versão do python*
```python3 -V```

*CORRIGIR ERRO DO APT / DPKG*

```sudo apt install python3-apt --fix-missing```
```sudo apt remove python3-apt```
```sudo apt autoremove```
```sudo apt autoclean```
```sudo apt install python3-apt```

*tente instalar o script novamente*

### Ou
```
curl -sL https://raw.githubusercontent.com/WdsUtilidades/CheckUser/main/install.sh > install.sh; chmod a+x install.sh; ./install.sh
```
 *Opcao 1*

# Atualização
```
python3 -m pip install --upgrade git+https://github.com/WdsUtilidades/CheckUser.git
```

### Ou
```
curl -sL https://raw.githubusercontent.com/WdsUtilidades/CheckUser/master/install.sh > install.sh; chmod a+x install.sh; ./install.sh
```
 *Opcao 2*

# Como usar
```
checkuser --help
```
# CheckUserGL
