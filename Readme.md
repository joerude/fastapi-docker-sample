### Разработка API с помощью FastAPI, SQLAlchemy, Alembic, PostgreSQL, Uvicorn и Docker.

Создание API с использованием FastAPI с Uvicorn (получение и отправка данных),
SQLAlchemy + Alembic для управления миграциями, PostgreSQL + PGAdmin,
развернутые в Docker/Docker-Compose.

# Запуск

<p>Настройте параметры конфигураций базы данных Postgres в файле <b>.env</b></p>

В командой строке запустите
```
docker-compose build
docker-compose up
```

После всех установок перейдите по адресу: http://0.0.0.0:8000

Документация API находится по адресу: http://0.0.0.0:8000/docs
