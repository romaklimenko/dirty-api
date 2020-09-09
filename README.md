# Эй Пи Ай

Postman-коллекция с API d3.ru.

Для работы вам понадобится настроить environment. Возьмите файл `d3.ru.postman_environment.template.json`,
переименуйте в `d3.ru.postman_environment.json`, заполните следующие значения:

- `sid` – ключ сессии, смотрите в cookies.
- `uid` – идентификатор пользователя.
- `username` – юзернейм, очевидно.
- `password` – пароль.
- `domain` – домен. У пользователя должен быть к нему административный доступ. Используется, для банов, например.
- `csrf_token` – CSRF-токен, найдете его на любой странице с формой.

Коллекция доступна онлайн: https://documenter.getpostman.com/view/1012355/TVCgznCm
