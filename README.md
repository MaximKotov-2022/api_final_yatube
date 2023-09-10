# api_final_yatube
Проект API для проекта YaTube. Созданы адреса и представления для обработки запросов в приложении api.
Сериализация данных для всех моделей проекта (Post, Comment, Group, Follow).
Обработка GET, POST, PATCH, PUT и DELETE запросов к базе данных проекта Yatube


## Установка и запуск
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/MaximKotov-2022/api_final_yatube
```
```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:
```
python3 -m venv venv
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


## Техническое описание проекта
### Функции
+ Получение постов для любых пользователей
+ Написание постов для авторизированных пользователей
+ Разбиение постов на группы
+ Получение и работа с комментариями к постам
+ Подписка на понравившегося автора
+ Подписка на авторов
+ Аутентификацию по JWT-токену


## Используемые технологии
+ Python
+ Django
+ JWT
+ Djoser

## Авторы
+ **Котов Максим** [MaximKotov-2022](https://github.com/MaximKotov-2022)
