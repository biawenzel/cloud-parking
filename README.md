# cloud-parking
Desafio de projeto do professor Sandro Giacomozzi, feito durante bootcamp da DIO com o objetivo de de desenvolver um conjunto de API’s utilizando Spring Boot para controlar um estacionamento de veículos. Serão controlados a entrada, saída e valor a ser cobrado do cliente.

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=Niver14/03 -d postgres:10-alpine