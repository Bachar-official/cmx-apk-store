# Cinimex app store (backend)

## Мотивация

Идея данного проекта - централизованное хранение и отдача apk файлов для установки на мобильные устройства.

# Загрузка файла
Загрузка производится методом POST запроса на хост с портом 1337 и следующим payload:

```{"fileName": "Название приложения",
    "version": "Версия артефакта",
    "arch": "Архитектура apk",
    "package": "Пакет приложения",
    "body": "Файл apk в BASE64"}```
