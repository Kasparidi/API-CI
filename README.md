### DESCRIPTION
Дан целевой сервис для настройки CI.

### [TASK](https://github.com/netology-code/aqa-homeworks/tree/master/api-ci)
1. Настроить для проекта CI. Удостовериться, что CI показывает, что сборка
падает (в процессе сборки будут автоматически прогоняться все авто-тесты).
1. Изучить построение JSON schema.
1. Добавить в зависимость и сохранить в ресурсах.
1. Доработать схему, найдите способ валидации значения поля на два из возможных значений: "RUB" или "USD"   
1. Убедиться, что тесты падают при изменении "RUB" на "RUR".git 

### LAUNCH
1. Запускаем приложение командой ``java -jar artifacts/app-mbank.jar``
1. Запускаем тесты ``gradlew test``
1. Доступно в браузере http://localhost:9999/api/v1/demo/accounts

### TOOLS
REST-assured, JSON schema, AppVeyor

### CI

[![Build status](https://ci.appveyor.com/api/projects/status/thucbuk5gosnilf9?svg=true)](https://ci.appveyor.com/project/Kasparidi/api-ci)