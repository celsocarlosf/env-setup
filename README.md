# env-setup
Notebook and environment setup and configurations

# Dev Seupt

### os
Linux Mint
```
sudo apt install git 
```

### php + apache
```
sudo apt install php7.4 php7.4-mbstring php7.4-dom php7.4-soap php7.4-zip apache2 -y
```

Alterar propriedade da pasta www
```
sudo chown -R USER /var/www/
```

### composer
```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
```
```
php -r "if (hash_file('sha384', 'composer-setup.php') === '906a84df04cea2aa72f40b5f787e49f22d4c2f19492ac310e8cba5b96ac8b64115ac402c8cd292b8a03482574915d1a8') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
```
```
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```
```
php -r "unlink('composer-setup.php');"
```


### node 
```
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 
```

```
source ~/.profile
```

```
nvm install --lts
```


###

