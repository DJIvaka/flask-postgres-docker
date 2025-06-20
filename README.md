# Flask + PostgreSQL + Docker Compose

## Как се стартира проекта

```bash
docker compose up --build
```

## Структура на проекта

- `backend/`: Flask приложение
- `db/init.sql`: SQL скрипт за създаване на таблица `users`
- `compose.yml`: Docker Compose конфигурация

## Компоненти

- Flask уеб сървър, достъпен на `localhost:5000`
- PostgreSQL база данни с примерна таблица

## Комуникация

Flask се свързва с базата чрез `host='db'` – това е името на контейнера от Compose.
