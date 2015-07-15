# Участие в разработке

## Запуск автотестов

Для проверки правильности внесенных изменений рекомендуем выполнить следующую команду в корневой директории и убедиться, что все тесты выполнились без ошибок:

    mocha

## Запуск автотестов с отчетом о покрытии кода автотестами

Чтобы узнать о степени покрытия исходного кода автотестами, следует выполнить следующую команду:

    make coverage

После этого откройте в браузере файл `html-report/index.html`. Красным цветом в отчете будут помечены строки, которые ни разу не выполнялись во время работы тестов.