# DevOps diploma application

Тестовое статическое приложение на nginx для демонстрации сборки Docker-образа и CI/CD-деплоя.

## Сборка образа

```bash
docker build -t devops-diplom:local .
```

## Запуск через Docker Compose

Создайте `.env` на основе `.env.example`, укажите имя пользователя Docker Hub, затем выполните:

```bash
docker compose pull
docker compose up -d
```

Приложение будет доступно на порту 80.
