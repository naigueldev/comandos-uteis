### Instalar rvm [Rvm Install](https://rvm.io/rvm/install)

Rodar o comando:
```
gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

Depois rodar esse comando:
```
\curl -sSL https://get.rvm.io | bash
```

### Criar um contexto com uma versão do Ruby

```
rvm use 2.7.0@rep_nota_1000 --create --rvmrc
```

### ERRO: Rvm ruby Permissions denied
Possível solução [1]:
```
rvm fix-permissions
```

### ERRO: Could not load OpenSSL
Possível solução [1]:
```
rvm install 2.7.0 --with-openssl-dir=`brew --prefix openssl
```