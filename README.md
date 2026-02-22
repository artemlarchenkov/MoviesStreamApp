# MoviesStreamApp
## Описание
**MoviesStreamApp** — это серверная часть приложения на Go для работы с базой фильмов.
Позволяет:

* Добавлять фильмы в базу данных
* Получать список фильмов
* Работа с пользователями
* Простейший REST API

---

## Установка

1. Склонировать репозиторий:

```bash
git clone https://github.com/artemlarchenkov/MoviesStreamApp.git
cd MoviesStreamApp/Server/StreamMovies
```

2. Установить зависимости:

```bash
go mod tidy
```
## Настройка

* Настройте переменные окружения (если нужны)
* Подключите базу данных MongoDB
---
## Запуск сервера
```bash
go run main.go
---
## API

Пример эндпоинтов:

* `GET /movies` — получить список фильмов
* `POST /movies` — добавить фильм
* `POST /users` — добавить пользователя

---
