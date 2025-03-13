# api_final
api final
# API для Yatube

## Описание
Этот проект представляет собой API для социальной сети Yatube. API позволяет пользователям создавать посты, подписываться на других пользователей, комментировать посты и многое другое.

## Установка
1. Клонируйте репозиторий:
   git clone https://github.com/NatalyCEO/api_final_yatube.git
   cd api_final_yatube
2. Создайте и активируйте виртуальное окружение:
    python3 -m venv venv
    source venv/bin/activate
3. Установите зависимости:
    pip install -r requirements.txt
4. Выполните миграции:
    python manage.py migrate
5. Запустите сервер:
    python manage.py runserver