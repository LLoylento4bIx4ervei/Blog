# Blog
Этот репозиторий о небольшом блоге .
# Запуск приложения
Необходимо установить зависимости из requirements.txt:

`pip install -r requirements.txt`

Применить миграции:
`python manage.py migrate`
Запустить сервер:
`python manage.py runserver`

# Dockerfile
Команда для запуска Dockerfile:

`docker build .`
# Docker compose
Для запуска сервисов БД необходимо использовать файл docker-compose.yml и команды:

`docker compose build`
`docker compose up`
