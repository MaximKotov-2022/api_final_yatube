# api_final

# Описание

Проект представляет собой API для проекта yatube.

Функционал:
Авторизация по JWT токену

Сериализация данных для всех моделей проекта (Post, Comment, Group, Follow)

Обработка GET, POST, PATCH, PUT и DELETE запросов к базе данных проекта Yatube

### Технологии
+ Python 3.7
+ Django 2.2.19
+ Django Rest Framework 3.12.4
+ JWT + Djoser


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/MaximKotov-2022/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/bin/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
