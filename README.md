# Docker

## Conteúdos

1. O que são Containers?
2. Como funcionam os Containers?
3. Como o Docker funciona?
4. Principais comando utilizando Docker
5. Dockerfile
6. ToDo

---

## O que são Containers?

> Um container é um padrão de unidade de software que empacota código e todas as dependências de uma aplicação fazendo
> que a mesma seja executada rapidamente de uma forma confiável de um ambiente computacional para o outro.
> Fonte: [Docker](https://www.docker.com/resources/what-container/)

## Como funcionam os Containers?
>

## Como o Docker funciona?
>

## Principais comando utilizando Docker

+ [docker info](https://docs.docker.com/engine/reference/commandline/info/) - Utilizado para verificar as informações de nosso host.
+ [docker version](https://docs.docker.com/engine/reference/commandline/version/) - Utilizado para verificar a versão do Docker.
+ [docker ps](https://docs.docker.com/engine/reference/commandline/ps/) - Utilizado para lista os containers.
+ [docker search (parametro)](https://docs.docker.com/engine/reference/commandline/search/) - Utilizado para procurarmos uma imagem, nós podemos utilizar o comando a baixo com o parâmetro nome Ex.: ubuntu, dotnetcore, node… etc, assim ele irá buscar as imagens que são compatíveis com o nosso server.
+ [docker pull (parametro)](https://docs.docker.com/engine/reference/commandline/pull/) - Quando encontrarmos a imagem que precisamos para a nossa aplicação, nós precisamos baixar ela para o nosso host.
+ [docker run (nome da imagem)](https://docs.docker.com/engine/reference/commandline/run/) - Para que nós possamos criar um contêiner, nós precisamos de uma imagem. Caso você não tenha essa imagem no seu host ainda ele irá até o repositório central e irá baixar ela para o seu host, em seguida ele irá criar o contêiner.
+ [docker stats (id ou apelido do container)](https://docs.docker.com/engine/reference/commandline/stats/) - Para que possamos ter informações sobre um contêiner como: ID, % de uso de CPU, Memória usada e limite, I/O de internet e outros processos de I/O

## Dockerfile

## ToDo
