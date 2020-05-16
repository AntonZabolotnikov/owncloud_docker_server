## Запуск проекта
- В корне выполнить команду `docker-compose up -d`
- Проект будет доступен на порту `80`

## Файл .env
для запуска проекта нужно создать в корне файл `.env` и в нем прописать:
```
OWNCLOUD_VERSION=10.4.1
OWNCLOUD_DOMAIN=localhost
ADMIN_USERNAME=admin
ADMIN_PASSWORD=admin_pass
HTTP_PORT=80:8080
```