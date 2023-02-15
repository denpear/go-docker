Source: https://nuancesprog.ru/p/5657/

#I had to remove this package from go.mod
go get github.com/githubnemo/CompileDaemon@none

docker-compose up --force-recreate
docker-compose rm -f
docker-compose pull
docker-compose up --build -d
