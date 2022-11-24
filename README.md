# discord-bot

# ❓ FAQ

Требуется: Node.js, discord.js, MongoDB

Редактировать функционал можно в config.js отключая/включая определенные функции
Обязательно вставить токен бота и MongoDB в .env, также нужно добавить айди владельца бота в config.js, а также можно изменить префикс в config.js

Для включения слэщ-команд поставить значения в config.js SLASH = true, CONTEXT = true, GLOBAL = true, а также вставить ID канала в TEST_GUILD_ID

>Установка пакетов

```npm install```

>Запуск бота

```node bot.js```
или 
```npm run start```

Функционал бота можно узнать через /help (вместо слэш ваш префикс)

Для настройки мониторинга вставьте http://localhost:8080/api/callback в ваше приложение OAuth2 на портале разработчиков дискорд

```
 DASHBOARD: {
    enabled: true, // enable or disable dashboard
    baseURL: "http://localhost:8080", // base url
    failureURL: "http://localhost:8080", // failure redirect url
    port: "8080", // port to run the bot on
  },
```
