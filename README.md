# DBeaver + PostgreSQL + MySQL в Docker

Этот `docker-compose.yml` разворачивает **CloudBeaver**, **PostgreSQL** и **MySQL** в контейнерах.  
CloudBeaver используется для удобного управления базами данных через веб-интерфейс.

## Запуск контейнеров

### Запуск образов в фоновом режиме:
```bash
docker-compose up -d
```

### Остановка всех сервисов (контейнеров)
```bash
docker-compose down
```

### Остановка всех сервисов (контейнеров) с удалением данных:
```bash
docker-compose down -v
```

## Дополнительная информация
CloudBeaver работает на порту `8978`, доступ по `localhost:8978`.

PostgreSQL доступен на `5432`

MySQL доступен на `3306`

![image](https://github.com/user-attachments/assets/5c60bac7-92c8-4de5-9d70-6c09c02e17d2)

