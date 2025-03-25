# 🤖 Sorhy AI Telegram Бот

## 📝 Описание
Этот проект представляет собой Telegram бота для генерации ответов на сообщения пользователей. Бот работает на Node.js и может быть легко настроен и развернут.

## ✨ Особенности
- 💬 Обработка текстовых сообщений от пользователей
- 🧠 Генерация ответов с использованием Mistral AI
- ⚙️ Настраиваемые параметры генерации (температура, длина ответов)
- 🔄 Поддержка контекста диалога

## 🛠️ Технологии
- Node.js
- node-telegram-bot-api
- Mistral AI API
- axios
- dotenv

## 🚀 Установка и запуск

### Предварительные требования
- Node.js (версия 14+)
- Telegram Bot Token (получить у [@BotFather](https://t.me/BotFather))
- Mistral API ключ

### Шаги установки
1. Клонируйте репозиторий:
```bash
git clone https://github.com/FarkhodovIslom/SorhyAI_telegram-bot.git
cd Mistral-tg-bot
```

2. Установите зависимости:
```bash
npm install
```

3. Создайте файл `.env` в корневой директории проекта и добавьте следующие строки:
```
TELEGRAM_BOT_TOKEN=ваш_токен_телеграм_бота
MISTRAL_API_KEY=ваш_ключ_api_mistral
```

4. Запустите бота:
```bash
node index.js
```

## 💡 Использование
1. Найдите своего бота в Telegram по имени пользователя
2. Отправьте любое сообщение
3. Получите ответ, сгенерированный с помощью Mistral AI

## 🛣️ Планы развития
- [ ] Добавление системы пользовательских настроек
- [ ] Интеграция с базой данных для хранения истории диалогов
- [ ] Поддержка групповых чатов
- [ ] Добавление дополнительных команд для настройки параметров генерации


## 🙏 Благодарности
- [Mistral AI](https://mistral.ai/) за предоставление API
- [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) за удобную библиотеку
