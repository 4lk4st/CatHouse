# Технологии, использованные в данном проекте:
- Python 3.9
- Django 3.2.3
- Django REST Framework 3.12.4
- Djoser 2.1.0
- Psycopg 2.9.3

#  Описание:
Ресурс KittyGram предназначен для публикации информации о Ваших котиках и кошечках! Реализован функционал регистрации пользователей, внесение записей в базу данных об основных параметрах котиков, в том числе реализована работа с полями цвета, записями через связанные модели.

# Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
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
