# FinTrack: Менеджер личных финансов

FinTrack - это приложение для управления личными финансами. Оно позволяет пользователям отслеживать свои расходы и доходы, создавать бюджеты, управлять долгами, устанавливать финансовые цели и многое другое.

## Структура репозитория

- **server**: Здесь находится серверная часть приложения. Это место, где происходит обработка данных, взаимодействие с базой данных и обработка запросов от клиентской части.
- **client**: Эта папка содержит клиентскую часть приложения. Здесь находится интерфейс пользователя, взаимодействие с пользователем и отображение данных.

## Установка и запуск

1. Клонируйте репозиторий:

```
git clone <URL-репозитория>
cd FinTrack
```

2. Установите зависимости для сервера и клиента:

```
cd server
npm install

cd ../client
npm install
```

3. Запустите сервер и клиент:

```
# В папке server/
npm start

# В папке client/
npm start
```

После этого вы сможете открыть приложение в браузере по адресу http://localhost:3000/.

## Контрибуция

Если у вас есть предложения по улучшению этого проекта, пожалуйста, создайте новый Issue или Pull Request. Мы приветствуем ваш вклад!