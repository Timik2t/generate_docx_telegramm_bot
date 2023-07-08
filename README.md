# generate_docx_telegramm_bot

## Описание проекта

Проект generate_docx_telegramm_bot представляет собой Telegram-бот, способный генерировать документы формата Word (docx) на основе текстовых сообщений, отправленных пользователями.

## Используемые технологии

- Python
- Telebot (библиотека для работы с Telegram API)
- python-docx (библиотека для работы с документами формата Word)
- python-dotenv (библиотека для загрузки переменных окружения из файла .env)

## Функциональность

Бот генерирует документы формата Word на основе текстовых сообщений.  Сгенерированные документы отправляются обратно пользователю в чате.


## Подготовка и запуск проекта

1. Склонируйте репозиторий на локальную машину:

    ```bash
    git clone git@github.com:Timik2t/generate_docx_telegramm_bot.git
    ```

2. Создайте и активируйте виртуальное окружение:

    ```bash
    python -m venv venv
    ```

    Активация окружения
    ```bash
    # Windows
    source venv/Scripts/activate
    ```
    ```bash
    # Linux
    source venv/bin/activate
    ```
3. Установите зависимости:

    ```bash
    pip install -r requirements.txt
    ```
4. Зарегистрируйте бота
    Для этого пишем боту `@BotFather` команду `/newbot`, после этого даем боту имя и тэг. После этих действий бот отправит нам токен, который никому давать нельзя.

5. Создайте файл .env в корневой папке проекта и укажите в нем необходимые переменные окружения:
    ```bash
    BOT_TOKEN=<токен вашего Telegram-бота>
    ```
6. Запуск проекта:
    ```bash
    python text_to_docx_bot.py
    ```
## Использование бота

Найдите бота в Telegram по его имени или добавьте его в свои контакты.
Начните диалог с ботом, отправив ему команду `/start`.
Бот пришлет вам сообщение с кнопкой "Отправить текст".
Нажмите на кнопку и отправьте боту текстовое сообщение.
Бот сгенерирует документ на основе вашего сообщения и отправит его вам в чате.
### Автор

[Исхаков Тимур](https://github.com/Timik2t)
