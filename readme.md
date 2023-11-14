# Курсовой проект

## запуск dev версии
```shell
docker compose up --build
```

## запуск предварительной сборки
```shell
docker compose -f docker-compose-build.yml up --build 
```

## запуск product версии
```shell
docker compose -f docker-compose-prod.yml up
```
