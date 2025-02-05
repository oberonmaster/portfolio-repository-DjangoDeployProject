Это веб-приложение на Django, предназначенное для демонстрации моего портфолио и навыков разработки.

Данный репозиторий позволяет развернуть на удаленном сервере движок интернет магазина с реализованными авторизацией и аутентификацией, созданием карточек товаров и их описаний и т.д.

## Установка

1. **Клонирование репозитория:**

   ```bash
   git clone https://github.com/oberonmaster/portfolio-repository-DjangoDeployProject.git
   cd portfolio-repository-DjangoDeployProject
   ```

2. **Создание и настройка виртуального окружения:**

   python3 -m venv venv
   source venv/bin/activate  

   # Для Windows используйте venv\Scripts\activate

3. **Установка зависимостей с помощью Poetry:**

   poetry install

4. **Настройка переменных окружения:**

   Скопируйте файл `.env.template` в `.env` и заполните необходимые переменные.

5. **Применение миграций базы данных:**

   python manage.py migrate

6. **Запуск сервера разработки:**

   python manage.py runserver

## Использование Docker

Альтернативно, вы можете использовать Docker для запуска приложения.

1. **Сборка и запуск контейнеров:**

   docker-compose up --build

   Это запустит приложение и необходимые сервисы, определенные в `docker-compose.yaml`.