# Проект Movies Explorer: бэкенд
## Директории

`/routes` — папка с файлами роутера  
`/controllers` — папка с файлами контроллеров пользователя и карточек фильмов   
`/models` — папка с файлами описания схем пользователя и карточки фильма
`/errors` — папка с классами ошибок
`/middlewares` — авторизация и логгер

## Как запустить проект локально

* Должна быть установлена MongoDB, название базы - bitfilmsdb, MONGODB_URI = 'mongodb://localhost:27017/bitfilmsdb'
* Клонируйте проект, разверните его в локальную папку и перейдите в нее
* Убедитесь, что Node.js и NPM установлены
* Установите зависимости:
```shell
npm install
```
* Запуск сервера в dev-режиме с hot-reload:
```shell
npm run dev
```
* Запуск сервера в режиме production:
```shell
npm run start
```
## Live demo

API URL: https://api.deadforstree.nomoreparties.sbs


Спасибо за внимание!
