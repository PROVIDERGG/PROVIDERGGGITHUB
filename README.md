# LogWriter

## Описание

LogWriter — это приложение для агрегации логов веб-сервера Apache. Приложение парсит access логи Apache, сохраняет их в базу данных и предоставляет инструменты для просмотра и анализа данных через консоль и API. Поддерживается авторизация пользователей с различными уровнями доступа и мониторинг ошибок в реальном времени.

## Требования

- Python 3.x
- MySQL или PostgreSQL
- Установленные зависимости из `requirements.txt`

## Установка

1. Скачайте файлы проекта и поместите их в необходимую директорию.

2. Установите необходимые зависимости:

   ```bash
   pip install -r requirements.txt
