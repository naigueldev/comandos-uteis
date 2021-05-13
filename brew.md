### ERRO: Permissão do usuário para pastas do brew
```
sudo chown -R $(whoami) $(brew --prefix)/*
```