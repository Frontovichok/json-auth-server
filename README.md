JSON сервер для тестового приложения. Умеет авторизовывать пользователей и хранить(добавлять, изменять, удалять) данные(контакты)

Для запуска нужно клонировать репозиторий, войти в созданную папку, установить зависимости командой:

```bash
yarn install
```

Ну а после установки запустить сервер командой (запустится на порту 3000, порт не изменять! т.к. приложение обращается именно на него):

```bash
json-server db.json -m ./node_modules/json-server-auth
# при этом json-server-auth должен быть установлен глобально
```
