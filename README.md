# docker-microservicos
Sistema de de avaliação de filmes
Nesse sistema temos uma particularidade, ele possui a integração de 3 serviços diferentes e dois bancos de dados
Utilizamos aqui Mongo DB e Postgres

# Build das imagens e execução da aplicação

Executar a linha de comando para fazer o build da aplicação e sua execução: </br></br>
docker compose up -d</br></br>
Para listar o container em execução: </br>
`docker container ls` </br></br>
Para a aplicação em execução: </br>
`docker-compose down` </br></br>

#Verificando as imagens enviadas para o docker Hub
[Clique aqui para verificar a imagem do front no Hub](https://hub.docker.com/repository/docker/evvolpe/rotten-potatoes-ms)
[Clique aqui para verificar a imagem do serviço de filmes no Hub](https://hub.docker.com/repository/docker/evvolpe/movies)
[Clique aqui para verificar a imagem do serviço de avaliação no Hub](https://hub.docker.com/repository/docker/evvolpe/review)
