# Курсовой проект

Бэкенд-приложение с API для доски объявления с чатом.   
[Подробное тех.задание здесь](https://github.com/netology-code/ndse-diplom)      
[Копия тех.задания здесь](https://github.com/riadesigner/course-app/blob/main/original-task.md)   


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


### Характеристики приложения

### host/post

- app -> localhost:8000   
- Mongo-Express -> localhost:8082   

1. Приложение содержит следующие **базовые** модули:

- 1.1. Пользователи.
- 1.2. Объявления.
- 1.3. Чат.




