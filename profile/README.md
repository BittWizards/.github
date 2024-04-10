# MVP CRM-системы для Амбассадоров Яндекс Практикума.

[Посмотреть проект можно по ссылке](https://ambassadors.sytes.net/)

## Оглавление <a id="contents"></a>

1. [О проекте](#about)
2. [Авторы проекта](#authors)
4. [Стек технологий](#tools)
5. [Функционал](#functional)
6. [Установка зависимостей](#installation)
7. [Запуск](#start)
8. [Наполнение БД](#database)
9. [Telegram бот](#bot)

## О проекте <a id="about"></a>

MVP CRM-системы для Амбассадоров Яндекс Практикума.

## Авторы проекта <a id="authors"></a>
Команда:

- Product manager
  - Смирнов Алексей

- Project manager
  - Кравцова Елена

- Business analytics
  - Филимонова Ольга
  - Кашина Елена

- System analytics
  - Карпетис Александр
  - Гогорян Даниил
  - Ольховская Елена

- Designers
  - Каравашкина Александра
  - Каткова Анастасия
  - Храковская Ирина
  - Теплова Полина

- Frontend
  - [Шматенко Наталья](https://github.com/NatashaSolntseva)
  - [Тюлюкин Роман](https://github.com/JayWeee)
  - [Фрикина София](https://github.com/SofiaFrikina)

- Backend
  - [Синюков Алексей](https://github.com/aleksey2299-1)
  - [Дунаева Клавдия](https://github.com/KlavaD)
  - [Дровнин Павел](https://github.com/pashpiter)
  - [Варачев Андрей](https://github.com/Dartanyun)

## Стек технологий <a id="tools"></a>

[![Typescript](https://img.shields.io/badge/TypeScript-%23404d59.svg?style=for-the-badge&logo=typescript&logoColor=blue)](https://www.typescriptlang.org/)
[![Javascript](https://img.shields.io/badge/javascript-%23404d59.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/ru/docs/Web/JavaScript)
[![Redux](https://img.shields.io/badge/Redux-%23404d59.svg?style=for-the-badge&logo=Redux&logoColor=violet)](https://redux.js.org/)
[![React](https://img.shields.io/badge/react-%23404d59.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/)
[![CSS3](https://img.shields.io/badge/css3-%23404d59.svg?style=for-the-badge&logo=css3&logoColor=lightblue)](https://www.w3.org/Style/CSS/)
[![SASS](https://img.shields.io/badge/SASS-%23404d59.svg?style=for-the-badge&logo=SASS&logoColor=hotpink)](https://sass-lang.com/)
[![HTML5](https://img.shields.io/badge/html5-%23404d59.svg?style=for-the-badge&logo=html5&logoColor=orange)](https://html.spec.whatwg.org/multipage/)
[![MUI](https://img.shields.io/badge/mui-%23404d59.svg?style=for-the-badge&logo=mui&logoColor=007FFF)](https://mui.com/)
[![React Hook Form](https://img.shields.io/badge/reacthookform-%23404d59.svg?style=for-the-badge&logo=mui&logoColor=EC5990)](https://react-hook-form.com/)

[![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-%204.2-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/DjangoRESTFramework-%203.14.0-blue?style=for-the-badge&logo=django)](https://www.django-rest-framework.org/)
[![Celery](https://img.shields.io/badge/Celery-%205.3.6-blue?style=for-the-badge&logo=celery)](https://docs.celeryq.dev/en/stable/)
[![Redis](https://img.shields.io/badge/Redis-%205.0.1-blue?style=for-the-badge&logo=redis)](https://redis.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%2016-blue?style=for-the-badge&logo=PostgreSQL)]([https://www.postgresql.org/])
[![Gunicorn](https://img.shields.io/badge/Gunicorn-%2020.1.0-blue?style=for-the-badge&logo=gunicorn)](https://gunicorn.org/)
[![drf-spectacular](https://img.shields.io/badge/drf--spectacular-0.27.0-blue?style=for-the-badge)](https://drf-spectacular.readthedocs.io/)
[![django-channels](https://img.shields.io/badge/django--channels-4.0.0-blue?style=for-the-badge)](https://channels.readthedocs.io/)

[![Swagger](https://img.shields.io/badge/Swagger-4A154B?style=for-the-badge&logo=swagger&logoColor=Black)](https://swagger.io/)
[![Docker](https://img.shields.io/badge/Docker-white?style=for-the-badge&logo=docker&logoColor=White)](https://www.docker.com/)
[![DockerCompose](https://img.shields.io/badge/Docker_Compose-34567C?style=for-the-badge&logo=docsdotrs&logoColor=White)](https://docs.docker.com/compose/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)](https://nginx.org/)
[![Certbot](https://img.shields.io/badge/certbot-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white)](https://certbot.eff.org/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/ru)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://docs.github.com/en/actions)

## Функционал<a id="functional"></a>

1. Реализован базовый функционал CRM приложения.
2. Настроена интеграция с Яндекс Forms.
3. Настроена интеграция с Яндекс ID.
4. Подключен прототип telegram бота.
5. Реализована рассылка через email и telegram.

## Установка зависимостей для полного разворачивания проекта<a id="installation"></a>

1. Создайте и перейдите в директорию проекта:

```bash
mkdir forms
cd forms/
```

2. Скачайте и добавьте файл **docker-compose.production.yml** в директорию.

3. Cоздайте файл **.env**:

```bash
nano .env
```

Добавьте следующие строки и подставьте свои значения:
````dotenv
# postgres
POSTGRES_DB=DB                           # название db
POSTGRES_USER=USER                       # имя пользователя для db
POSTGRES_PASSWORD=PASSWORD               # пароль пользователя для db
DB_HOST=db                               # если поменять, то тогда нужно поменять название сервиса в docker-compose.production.yml
DB_PORT=5432                             # это порт для доступа к db

# django
SECRET_KEY=SECRET_KEY                    # SECRET_KEY в настройках django
DEBUG=False                              # режим debug (True или False)
ALLOWED_HOSTS=127.0.0.1 backend          # ваши адреса через пробел (пример:localhost 127.0.0.1 xxxx.com)

# certbot
GET_CERTS=False                          # True для получения сертификатов (обязательно укажите email в CERTBOT_EMAIL
CERTBOT_EMAIL=example@example.com        # Email для регистрации certbot
DOMAIN=exemple.com                       # Домен на котором вы разворачиваете

# tg bot
BOT_TOKEN=telegram_bot_token             # Токен телеграм бота, если вы планируете его использовать

# yandex ID
YANDEX_ID_CLIENT_SECRET=secret           # Client secret в приложении yandex ID

# mail
USE_SMTP=False                           # использовать ли настоящий сервис по отправке почты, иначе сообщения будут сохранятся внутри контейнера (папка sent_emails)
EMAIL_HOST=EMAIL_HOST                    # домен вашего email service
EMAIL_PORT=EMAIL_PORT                    # порт для подключения к серверу почты
EMAIL_HOST_USER=EMAIL_HOST_USER          # email с которого будет осуществлятся рассылка
EMAIL_HOST_PASSWORD=EMAIL_HOST_PASSWORD  # пароль для доступа со стороны стороннего приложения
EMAIL_USE_TLS=False                      # использовать TLS (True или False)
EMAIL_USE_SSL=True                       # использовать SSL (True или False)

# frontend
VITE_REACT_APP_BASE_URL='https://youradress.com'       # url для API запросов (можно не указывать, если используете docker-compose.production.yml)
VITE_REACT_APP_CLIENT_ID='ClientID'                    # идентификатор приложения для получения OAuth токена
VITE_REACT_APP_CURRENT_URL='https://youradress.com'    # url для приложения яндекс ID
````

4. [Установить docker](https://www.docker.com/get-started/)

В терминале linux это можно сделать так:

```bash
  sudo apt update
  sudo apt install curl
  curl -fSL https://get.docker.com -o get-docker.sh
  sudo sh ./get-docker.sh
  sudo apt install docker-compose-plugin
```

---

## Запуск <a id="start"></a>

1. Запустите контейнеры с проектом следующей командой (используйте флаг -d для запуска в фоновом режиме):

```bash
docker compose -f docker-compose.production.yml up
```

В терминале Linux могут потребоваться права суперпользователя:

```bash
sudo docker compose -f docker-compose.production.yml up
```

2. Для доступа в [админ-зону](http://localhost:8000/admin/):

Логин: `admin@admin.com`

Пароль: `admin`

## Наполнение БД <a id="database"></a>

Для импорта начальных данных воспользуйтесь командой:

```bash
docker compose exec backend python manage.py xml_import
```

После запуска проект можно будет посмотреть по [ссылке](http://localhost:8000/).

Посмотреть документацию:
[Swagger](http://localhost:8000/api/docs/)

## Telegram bot<a id="bot"></a>

Реализован небольшой функционал чат бота. Добавлено веб приложение для бота.

Для прослушивания уведомлений от telegram api используется webhook.

Чтобы установить вебхук для вашего домена воспользуетесь следующей командой:

```bash
docker compose exec backend python manage.py telegram_webhook -s
```


[Оглавление](#contents)

