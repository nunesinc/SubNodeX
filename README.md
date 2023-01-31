# Substrate node

Versão aprimorada para rodar o  substrate node usando docker docker. Baseado na versão de desenvolvimento do  substrate-node-template e substrate-front-end-template 

👷‍♂️ Testado em ambiente Windows com terminal WSL2

# How to run

1. É imprescindível que tenha o  [docker](https://docs.docker.com/engine/install/) & [docker-composer](https://docs.docker.com/compose/install/) instalados

2. Clone o SubNodeX e rode os seguintes comandos

```
$ git clone https://github.com/nunesinc/SubNodeX.git SubNodeX
$ cd SubNodeX
$ docker-compose build
$ docker-compose up

```


Como a imagem já está criada, nas próximas vezes, entre no diretório principal do SubNodex e dê um: 

```
$ docker-compose up
```

3. Abra o browser para acessar o front do SubNodeX:

- `http://localhost:8000` 


# References


1. [Substrate node template](https://github.com/substrate-developer-hub/substrate-node-template)
2. [Substrate front-end template](https://github.com/substrate-developer-hub/substrate-front-end-template)
3.  [Substrate] (https://docs.substrate.io/quick-start/)


Futuras alterações: Portugues e Inglês, Refatoramento de código

=== Atualização: 27/01/2023 ===