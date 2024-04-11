# Проект "Telegram-bot"

[![Python](https://img.shields.io/badge/-Python-464646?style=flat&logo=Python&logoColor=56C0C0&color=008080)](https://www.python.org/)
[![python-telegram-bot](https://img.shields.io/badge/-python-telegram-bot-464646?style=flat&logo=python-telegram-bot&logoColor=56C0C0&color=008080)](https://docs.python-telegram-bot.org/en/stable/index.html)

## Описание проекта "Telegram-bot"

Бот-ассистент обращаться к API сервиса Практикум.Домашка и узнает статус домашней работы: взята ли домашка в ревью, проверена ли она, а если проверена — то принял её ревьюер или вернул на доработку.

### Задачи telegram-бота:

- раз в 10 минут опрашивает API сервиса Практикум.Домашка и проверяет статус отправленной на ревью домашней работы;
- при обновлении статуса анализирует ответ API и отправляет соответствующее уведомление в Telegram;
- логирует свою работу и сообщает о важных проблемах сообщением в Telegram.

## Запуск проекта локально

- Клонируйте репозиторий и перейдите в него в командной строке:
```
git clone git@github.com:cskovec22/Telegram_bot.git
cd Telegram_bot
```

- Запустите файл `homework.py`

### Автор:  
*Васин Никита*  
**email:** *cskovec22@yandex.ru*  
**telegram:** *@cskovec22*  
