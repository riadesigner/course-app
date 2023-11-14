# Курсовой проект

Бэкенд-приложение с API для доски объявления с чатом.   
[Подробное ТЗ здесь](https://github.com/netology-code/ndse-diplom).
[Копия ТЗ здесь](https://github.com/riadesigner/course-app/original-task.md)   

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
