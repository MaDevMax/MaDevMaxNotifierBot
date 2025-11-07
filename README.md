# MaDevMax Notifier Bot 🔔

# Описание проекта
Telegram‑бот для автоматической рассылки уведомлений подписчикам.  
Написан на **Python 3.11+** с использованием библиотеки `telebot` (pyTelegramBotAPI).  

Бот позволяет пользователям подписываться на уведомления и получать рассылки администратором.


# ⚙️ Функционал
- `/start` — подписка на рассылку  
- `/stop` — отписка  
- `/help` — справка по командам  
- `/send текст` — администратор рассылает сообщение всем пользователям  
- Список пользователей сохраняется локально в файле `users.txt`


# 🧩 Технологии
- Python 3.11+  
- pyTelegramBotAPI (telebot)  
- Основные модули: `os`, `set`  
- Хранение пользователей в текстовом файле  


# 📦 Запуск локально
1. Склонировать репозиторий:  
   git clone https://github.com/MaDevMax/MaDevMaxNotifierBot.git
   cd MaDevMaxNotifierBot
   
2. Установить зависимости:
pip install -r requirements.txt

3. Вставить свой TOKEN и ADMIN_ID в код.

4. Запустить python notifier_bot.py
