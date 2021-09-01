# yamdb_final
### Описание
Благодаря этому проекту можно оценивать фильмы, писать рецензии.
### Технологии
Python 3.7
Django 3.0.5
### Установка
Для запуска программы введите команду:
- docker-compose up
Для создания суперпользователя введите команду:
- docker-compose exec web python manage.py createsuperuser
Для заполнения базы начальными данными введите команду:
- docker-compose exec web python manage.py migrate --noinput
### Автор
Дмитрий
![example workflow](https://github.com/TrueDi1905/yamdb_final/actions/workflows/main.yml/badge.svg)
