# Telegram-бот

Этот бот:
1. раз в 10 минут опрашивает API сервиса Практикум.Домашка и проверяет статус отправленной на ревью домашней работы;
2. при обновлении статуса анализирует ответ API и отправляет пользователю соответствующее уведомление в Telegram;
3. логирует свою работу и сообщает о важных проблемах сообщением в Telegram.

Технологии:
Python 3.7,
библиотека python-telegram-bot

# Как запустить проект
1. Клонировать репозиторий и перейти в него в командной строке:
git clone https://github.com/sukhovarina/Telegram-bot.git

2. Cоздать и активировать виртуальное окружение:

python -m venv env

source venv/Scripts/activate

3. Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip

pip install -r requirements.txt

4. Создать чат-бота Телеграм

5. Создать в директории файл .env и поместить туда необходимые токены в формате PRAKTIKUM_TOKEN = 'ххххххххх', TELEGRAM_TOKEN = 'ххххххххххх', TELEGRAM_CHAT_ID = 'ххххххххххх'

6. Запустить проект:

python homework.py
