<div align="center">

<h1>Aiogram Bot Tamplate</h1>

<img alt="Static Badge" src="https://img.shields.io/badge/tag-v1.0.0-blue?style=flat&logo=task&logoColor=blue&labelColor=gray">
<img alt="Static Badge" src="https://img.shields.io/badge/python-v3.13.0-FBDE02?style=flat&logo=python&logoColor=FBDE02&labelColor=gray">
<img alt="Static Badge" src="https://img.shields.io/badge/license-MIT-12C4C4?style=flat&logo=gitbook&logoColor=12C4C4">
<br>
<img alt="Static Badge" src="https://img.shields.io/badge/Aiogram-v3.15.0-8A2BE2?style=flat">

</div>


## 📌 Description
⠀

**Aiogram Bot Tamplate** — это шаблон для быстрого создания ботов в Telegram с использованием библиотеки aiogram. Он предоставляет базовую структуру проекта, включающую обработку команд, обработку сообщений, работу с базами данных (опционально), логирование и другие полезные функции. Шаблон помогает избежать рутинной работы по настройке проекта и позволяет разработчику сосредоточиться на логике бота.

⠀
## 🔨 Functions
⠀

* `/start` - запуск бота
* `/reply_kb` - Реплай клавиатура
* `/inline_kb` - Инлайн клавиатура
* `/fsm` - Запуск машинного состояния
* `/admin` - Команда для админа

⠀
## 🗂️ Template structure
⠀

```
source
────┬─
    ├───┤data
    │
    ├───┤db
    │
    ├───┤dialog
    │
    ├───┤exceptions
    │
    ├───┤locales
    │
    ├───┤misc
    │
    ├───┤telegram
    │   │ 
    │   ├───┤filters
    │   │ 
    │   ├───┤handlres
    │   │   │
    │   │   ├───┤admin
    │   │   │
    │   │   ├───┤extra
    │   │   │
    │   │   └───┤user
    │   │ 
    │   ├───┤keyboards
    │   │   │
    │   │   ├───┤callback
    │   │   │
    │   │   ├───┤inline
    │   │   │
    │   │   └───┤reply
    │   │ 
    │   ├───┤middlewares
    │   │ 
    │   └───┤states
    │
    ├───┤services
    │
    └───┤models
```

⠀
## 📋 About the content
⠀

### source/
* Корневая директория проекта, содержащая все основные модули и дополнительные компоненты.

### source/data
* Хранилище файлов: изображения, видео, логи и другие данные бота.

### source/db
* Модули для взаимодействия с базой данных (database).

### source/dialog
* Логика диалогов и управление состояниями пользователей с помощью `aiogram_dialog`.

### source/exceptions
* Определения пользовательских исключений для обработки ошибок.

### source/locales
* Файлы локализации для многоязычной поддержки бота.

### source/misc
* Вспомогательные функции и конфигурационные параметры.

### source/models
* Модели данных для взаимодействия с базой данных.

### source/services
* Внешние сервисы и интеграции (например, с API сторонних платформ).

### source/telegram
* Центральная директория с логикой бота: обработчики, коллбэки и т.д.

### source/telegram/filters
* Фильтры для обработки входящих сообщений.

### source/telegram/handlers
* Обработчики команд и сообщений бота.

### source/telegram/keyboards
* Определения и создание клавиатур для взаимодействия с пользователем.

### source/telegram/middlewares
* Здесь должны храниться middleware aiogram.

### source/telegram/states
* Для состояний машинных состояний (FSM).

⠀
## 🔓 Bot .env
⠀

| Имя переменной среды      | Описание                                                     |
|---------------------------|--------------------------------------------------------------|
| BOT_TOKEN                 | Токен от вашего Telegram-бота, вы можете получить его в Telegram в боте с логином @botfather.|
| LOGGER                    | |
| PARSE_MODE                | |
| ADMINS_ID                 | |
| DB_SQL                    | |
| DB_LIB                    | |
| DB_LOGIN                  | |
| DB_PASSWORD               | |
| DB_HOST                   | |
| DB_PORT                   | |
| DB_NAME                   | |

⠀
## 💼 Links
⠀

- Мой дискорд: [клик](https://discordapp.com/users/839816191254331413/)
- Мой тг: [клик](https://t.me/MrEnderman_YT)
<br>


_Если у вас остались какие-либо вопросы, или вы хотите мне помочь, то пишите мне в телеграмм или Дискорд._

⠀
## 👤 Author of Aiogram Template Bot
**© Алексеев Роман**
