# Fiap-checkpoint1

Checkpoint 1 de microsserviços docker

## Pré-requisitos

- Java 17+
- Docker 
- Acesso a internet
- Acesso ao Docker Hub

## Instalação

##### Clone do projeto
```
git clone https://github.com/JulioCesarLB/fiap-checkpoint1
```

## Execução


##### Docker

######Criação de imagem 
```
docker build -t fiap-checkpoint1 .
```
######Execução da imagem 
```
docker run -p 8080:8080 -e PROFILE=prd juliocesarlb/fiap-checkpoint1
docker run -p 8080:8080 -e PROFILE=dev juliocesarlb/fiap-checkpoint1
docker run -p 8080:8080 -e PROFILE=stg juliocesarlb/fiap-checkpoint1
```


## Contatos

- Desenvolvedor 1 - desenvolvedor1@email.com
- Desenvolvedor 2 - desenvolvedor2@email.com
