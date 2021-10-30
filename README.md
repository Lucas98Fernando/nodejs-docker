# Desenvolvimento com Docker :sunglasses:

- Aprendendo a utilizar o Docker para criar containers de desenvolvimento.

## :computer: Comandos úteis:

- Criar uma imagem do container

```
docker build -t exemplo/nomedocontainer
```

- Rodar o projeto com o Docker

```
docker run -p 3000:3000 -d exemplo/nomedocontainer
```

- Visualizar os containers criados

```
docker ps
```

- Monitorar as alterações nos arquivos e refletir isso no browser

```
docker-compose up
```