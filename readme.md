1. Подключение к базе данных осуществляется по обычной схеме подключения к БД PostgreSQL
    Для базовых значений используются миграции FlyWay
2. Для просмотра документации Swagger нужно перейти по ссылке
   http://localhost:8080/webjars/swagger-ui/index.html
3. BirthDate выбрал String т.к. в случае необходимости можно будет распарсить с помощью LocalDate.parse(BirthDate); 