# Mindustry-Discord-Chat-RU
Этот плагин НЕ является моим, я просто его перевёл на русский язык из за своих нужд, а так же немного доработал.
Оригинальный плагин: https://github.com/King-BR/Mindustry-Discord-Chat

## Установка:
1. [Скачать](https://github.com/Lolip-p/Mindustry-Discord-Chat-RU/releases) и положить в папку mods
2. [Создать](https://discord.com/developers/applications) discord бота и **обязательно назвать** `[MD]`
3. Включить у бота 3 галочки: `PRESENCE INTENT`, `SERVER MEMBERS INTENT`, `MESSAGE CONTENT INTENT`
4. Создать токен и пригласить на ваш дискорд сервер
5. В файле конфига `config/mods/DiscordChat/config.json` в поле рядом с `bot_token` вставить токен бота, рядом с `channel_chat` вставить ID вашего дискорд чата где вы будете общаться

## Мои изменения:
1. Перевод сообщений выводимых в чат дискорда
2. Добавлена поддержка сообщений от ботов (чтобы сообщения не создавали ЭХО, **обязательно назовите бота** `[MD]`)

## Команды:
Изменить префикс вызова команд можно в `config/mods/DiscordChat/config.json`
1. **ip** - если вы в конфиге `config/mods/DiscordChat/config.json` вставили в поле `server_ip` ip адрес вашего сервера, он будет выводится этой командой
2. **gameinfo** или **gi** - вывод игровой информации
3. **playerinfo** или **pi *<ник игрока>*** - вывод информации об игроке с данным ником
