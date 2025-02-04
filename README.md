Это Django-приложение, предназначенное для развертывания на продакшн сервере. Оно включает в себя основные функции для быстрого старта веб-приложений с использованием Django.

## Особенности

- Аутентификация пользователей
- REST API для взаимодействия с клиентом
- Простая настройка и деплой
- Поддержка работы с базой данных

## Установка

Клонируйте репозиторий:
   git clone https://github.com/oberonmaster/portfolio-repository-DjangoDeployProject.git

Перейдите в директорию проекта:

  cd portfolio-repository-DjangoDeployProject

Создайте виртуальное окружение (опционально):

  python -m venv venv

Активируйте виртуальное окружение:
  Для Windows: venv\Scripts\activate
  Для macOS/Linux: source venv/bin/activate

Установите зависимости:

  pip install -r requirements.txt

Примените миграции:
  python manage.py migrate

Запустите сервер:
  python manage.py runserver

Теперь приложение доступно по адресу http://127.0.0.1:8000.

Использование
После запуска приложения, вы сможете использовать его функциональность для работы с пользователями и API. 
