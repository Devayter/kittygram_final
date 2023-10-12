https://github.com/Devayter/kittygram_final/actions/workflows/main.yml/badge.svg

# Описание проекта:
Данный проект представляет сайт, где любой желающий может поделиться информацией о своем домашнем котике. Можно загружать фотографии, добавлять имя, цвет питомца и его достижения.


# Стек технологий, используемых в проекте:
- Django
- Django REST Framework
- React

# Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Devayter/infra_sprint1.git
```

```
cd infra_sprint1/backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

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
