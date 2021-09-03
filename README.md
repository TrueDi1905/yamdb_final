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
- Для ревьюера: Что касается развернутого проекта, то вчера у меня возникли проблемы с облаком, пришлось пересоздавать ВМ, теперь у меня проблемы с доступом к ней, вот уже второй день решаем вопрос и с тех. поддержкой и наставником. Поэтому нет возможности в данный момент загружать туда проект(до этого был загружен). В связи с этим не хотелось бы терять время, пока не решиться данный вопрос, дабы по скорее начать писать диплом.
- ![example workflow](https://github.com/TrueDi1905/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
