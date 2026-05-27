Repositório criado para documentar alguns comandos básicos do Docker.
Aluno: Julio Cesar Martins

# Comandos Docker

## docker --version
Mostra a versão instalada do Docker.

```bash
docker --version
```

---

## docker pull
Baixa uma imagem do Docker Hub.

```bash
docker pull ubuntu
```

---

## docker images
Lista as imagens instaladas.

```bash
docker images
```

---

## docker run
Executa um container.

```bash
docker run ubuntu
```

---

## docker run -it
Abre o terminal do container.

```bash
docker run -it ubuntu bash
```

---

## docker ps
Mostra containers ativos.

```bash
docker ps
```

---

## docker ps -a
Mostra todos os containers.

```bash
docker ps -a
```

---

## docker stop
Para um container.

```bash
docker stop ID
```

---

## docker rm
Remove um container.

```bash
docker rm ID
```

---

## docker rmi
Remove uma imagem.

```bash
docker rmi ubuntu
```