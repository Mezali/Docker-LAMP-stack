# DockerCompose-LAMP

Um simples stack de um servidor LAMP usando docker compose

# Pré-requisitos:


- docker 20.xx.xx

  

# Execução:

```
docker-compose -up -d // para iniciar os conteiners
```

```
docker-compose down // para desligar os conteiners
```

## Informações:

- Todo codigo deve ser inserido na pasta **/www/**
  
- Os aquivos do banco serão salvos na pasta **/data**
  
- Caso queira uma configuração mais expecifica, altere o arquivo **.env**
  
- Os DockerFiles estão dentro das pastas **/bin/**
  
- Caso queira iniciar um conteiner com as tabelas já inicializadas, adicione o sql dentro de **/bin/mariadb/banco.sql**
  
- O servidor web vai estar ligado na porta 80, para alterar isso mexa no **.env**
  
- o PhpMyAdmin, está na porta 8080
