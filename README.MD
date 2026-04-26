# Новостной портал

Новостной сайт, на котором любой желающий может оставить смешную и не очень новость.

## Описание
Новостной сайт, созданный с использованием микрофреймворка Flask в рамках обучения на курсе Пайтон Эксперт.

## Стек технологий
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить
1. Склонируй репозиторий.
2. Создай и активируй виртуальное окружение.
```commandline
py -m venv .venv
source .venv/Scripts/activate
```
3. Установи зависимости.
```commandline
pip install -r requirements.txt 

```
4. Создай файл .env и укажи настройки подключения к БД и секретный ключ.
```commandline
SQLALCHEMY_DATABASE_URI=sqlite:///db.sqlite3
SECRET_KEY=УПАДИ ЛИЦОМ НА КЛАВУ
```
5. Запусти приложение.
```commandline
flask run --debug
```

