# yamdb_final
### Описание
Благодаря этому проекту можно оценивать фильмы, писать рецензии.
Читатели могут оставлять отзывы и выставляют произведению рейтинг. Из множества оценок автоматически высчитывается средняя оценка произведения. Техническое описание проекта YaMDb

### Технологии
Python 3.7
Django 3.0.5
PostgreSQL 12.4
Docker 20.10.5
### Установка
Для запуска программы введите команду:
- docker-compose up
Для создания суперпользователя введите команду:
- docker-compose exec web python manage.py createsuperuser
Для заполнения базы начальными данными введите команду:
- docker-compose exec web python manage.py migrate --noinput
### Тест
Вы можете протестировать проект по ссылке http://130.193.55.11/admin/ (на данный момент сервер неактивен)
- login: fable@yandex.ru
- password: dima1212
- Ссылка на DockerHub - https://hub.docker.com/repository/docker/truedi1905/yamdb
### Автор
Дмитрий

- ![example workflow](https://github.com/TrueDi1905/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
