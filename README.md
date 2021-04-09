# Инструкция к запуску:
- Клонируем репозиторий: git clone

- Переходим в папку с проектом который хотим запустить Создаем виртуальное окружение: python -m venv test-django

- Активируем окружение: source test-django/bin/activate

- Устанавливаем необходимые пакеты: pip install -r requirements.txt

- Делаем миграцию БД: python manage.py migrate

- Запускаем: python manage.py runserver

## Документация к API написана с помощью swagger
После запуска сервера доступен по ссылке: http://127.0.0.1:8000/swagger/