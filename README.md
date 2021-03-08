### DESCRIPTION
Дан целевой сервис для настройки CI.

### [TASK](https://github.com/netology-code/aqa-homeworks/tree/master/api-ci)
Настроить для проекта CI. Удостовериться, что CI показывает, что сборка
падает (в процессе сборки будут автоматически прогоняться все авто-тесты).

### LAUNCH
1. Запускаем приложение командой ``java -jar artifacts/app-mbank.jar``
1. Запускаем тесты ``gradlew test``
1. Доступно в браузере http://localhost:9999/api/v1/demo/accounts

### TOOLS
REST-assured, JSON schema, AppVeyor

### CI

[![Build status](https://ci.appveyor.com/api/projects/status/thucbuk5gosnilf9?svg=true)](https://ci.appveyor.com/project/Kasparidi/api-ci)