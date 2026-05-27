# 10 Comandos Docker

## 1. Verificar versão do Docker
```bash
docker --version
```

## 2. Baixar uma imagem
```bash
docker pull ubuntu
```

## 3. Listar imagens
```bash
docker images
```

## 4. Criar e iniciar um container
```bash
docker run ubuntu
```

## 5. Executar container em modo interativo
```bash
docker run -it ubuntu bash
```

## 6. Listar containers ativos
```bash
docker ps
```

## 7. Listar todos os containers
```bash
docker ps -a
```

## 8. Parar um container
```bash
docker stop ID_DO_CONTAINER
```

## 9. Remover um container
```bash
docker rm ID_DO_CONTAINER
```

## 10. Remover uma imagem
```bash
docker rmi ubuntu
```