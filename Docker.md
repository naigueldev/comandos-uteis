### docker via bash
```
docker exec -it app_container bash
```

### docker-compose via bash
```
docker-compose exec app_container bash
```

### Deletar todas as imagens do sistema [Fonte: Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes-pt)
```
docker system prune -a
```

```
docker rmi $(docker images -a -q)
```

### Listar todos os containers ativos
```
docker ps -al
```

### Parar um container
```
docker stop CONTAINER_ID
```

### Parar todos os containers
```
docker stop $(docker ps -a -q)
```

### Deletar um container
```
docker rm CONTAINER ID
```

### Deletar todos os containers
```
docker rm $(docker ps -a -q)
```

### Iniciar todos os containers
```
docker start  $(docker ps -a -q) 
```

### Reniciar todos os containers
```
docker restart  $(docker ps -a -q) 
```