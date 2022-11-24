# discord-bot

Требуется: Node.js, discord.js, MongoDB

Редактировать функционал можно в config.js отключая/включая определенные функции
Обязательно вставить токен бота и MongoDB в .env, также нужно добавить айди владельца бота в config.js, а также можно изменить префикс в config.js

Для включения слэщ-команд поставить значения в config.js SLASH = true, CONTEXT = true, GLOBAL = true, а также вставить ID канала в TEST_GUILD_ID

Установка пакетов
npm install

Запуск бота
node bot.js или npm run start

Функционал бота можно узнать через /help (вместо слэш ваш префикс)
