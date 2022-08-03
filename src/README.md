# Iniciativa Devops - Aula 1

## Projeto - Conversão de Temperatura

Para montar a imagem docker:

* Entre no diretório **src**

```bash
cd src
```

* Execute o comando docker build
```bash
docker build -t pprogrammer/conversao-temperatura:v1 .
```

> Obs: Substitua o namespace **pprogrammer** pelo seu nome de usuário no Docker Hub

Para executar a imagem utilize o comando docker run:

```bash
docker run -d -p 8080:8080 pprogrammer/conversao-temperatura:v1
```