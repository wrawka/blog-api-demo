# YATUBE API
API учебного проекта "YATUBE" @ Яндекс.Практикум

---
![](https://img.shields.io/badge/OpenAPI-3.0.2-red)
![](https://img.shields.io/badge/python-3.7-blue)
![](https://img.shields.io/badge/django-2.2.6-brightgreen)

- [YATUBE API](#yatube-api)
    - [Что это](#что-это)
    - [Зачем это](#зачем-это)
    - [Как этим пользоваться:](#как-этим-пользоваться)
    - [Документация по API и примеры запросов](#документация-по-api-и-примеры-запросов)
    - [Благодарности](#благодарности)

### Что это

Имплементация restful-API для платформы блогов

### Зачем это

Научиться использовать на практике такие вещи как:
- вьюсеты и сериализаторы DRF
- аутентификация по JWT-токенам на связке Djoser / DRF-simplejwt
- разграничение доступа к  API на кастомных permissions

### Как этим пользоваться:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/wrawka/api_final_yatube
```

```
cd api_final_yatube
```

Создать и активировать виртуальное окружение:

```
python3 -m venv .venv
```

```
source .venv/Scripts/activate
```

```
python3 -m pip install --upgrade pip
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


### Документация по API и примеры запросов

После запуска локального сервера
документация по API и примеры запросов будет доступны по адресу:
**[http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/)**

### Благодарности

- команде учебного курса 
- участникам сообщества Stack Overflow
- моей маме