REST API социальной сети YaTube (Яндекс.Практикум) 
=====

Описание проекта
---------

API сервис для учебного курса Яндекс.Практикум. 

Системные требования
----------
* Python 3.7+
* Works on Linux, Windows, macOS, BSD

Стек технологий
----------
* Python 3.7
* Django 2.2 
* Django Rest Framework
* Pytest
* Simple-JWT
* SQLite3

Установка проекта из репозитория (Windows)
----------

1. Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone github.com/AnaKuzi/api_final_yatube.git

cd API_YaTube
```
2. Cоздать и активировать виртуальное окружение:
```bash
python -m venv env

source venv/scripts/activate
```
3. Установить зависимости из файла ```requirements.txt```:
```bash
python -m pip install --upgrade pip

pip install -r requirements.txt
```
4. Выполнить миграции:
```bash
cd yatube_api

python manage.py migrate
```
5. Запустить проект (в режиме сервера Django):
```bash
python manage.py runserver
```
Документация к проекту
----------
Документация для API после установки доступна по адресу ```/redoc/```.