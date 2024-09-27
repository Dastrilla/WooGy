# WooGy личный блог

Сайт для ведения личного блога

В этом проекте реализовано:

* Система тегов
* Генерация рекомендаций по публикациям на основе сложных QuerySets
* Пользовательские теги и фильтры
* Карта сайта
* Канал RSS
* Поисковая система, на основе полнотекстовой поисковой системы PostgreSQL


## Технологии
* Python 3.11.10
* Django 5.0.4
* PostgeSQL


## Запуск проекта:
* Склонировать проект на ваш компьютер с Github с помощью команды:
```bash
git clone https://github.com/Dastrilla/WooGy.git
```
* Создайте и активируйте виртуальное окружение:
```bash
python -m venv my_venv

source my_venv/bin/activate
```
* Установить зависимости из файла ```requirements.txt```:
```bash
pip install -r requirements.txt
```
* Выполните миграции:
```bash
python manage.py migrate
```
* Запустите проект:
```bash
python manage.py runserver
```

## Запуск

Раздел блог находиться по адресу
* http://127.0.0.1:8000/blog