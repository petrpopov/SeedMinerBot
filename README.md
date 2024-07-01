[<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/sho6ot)


![img1](.github/images/demo.png)

> 🇪🇳 README in english available [here](README-EN.md)

## Функционал  
| Функционал                                                     | Поддерживается  |
|----------------------------------------------------------------|:---------------:|
| Многопоточность                                                |        ✅        |
| Привязка прокси к сессии                                       |        ✅        |
| Авто-покупка предметов при наличии монет (tap, energy, charge) |        ✅        |
| Рандомное время сна между кликами                              |        ✅        |
| Рандомное количество кликов за запрос                          |        ✅        |
| Поддержка tdata / pyrogram .session / telethon .session        |        ✅        |


## [Настройки](https://github.com/shamhi/WormSlapBot/blob/main/.env-example)
| Настройка                | Описание                                                                                    |
|--------------------------|---------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Данные платформы, с которой запускать сессию Telegram (сток - Android)                      |


## Установка
Вы можете скачать [**Репозиторий**](https://github.com/shamhi/WormSlapBot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
~ >>> git clone https://github.com/shamhi/WormSlapBot.git 
~ >>> cd WormSlapBot

# Если вы используете Telethon сессии, то клонируйте ветку "converter"
~ >>> git clone https://github.com/shamhi/WormSlapBot.git -b converter
~ >>> cd WormSlapBot

# Linux
~/WormSlapBot >>> python3 -m venv venv
~/WormSlapBot >>> source venv/bin/activate
~/WormSlapBot >>> pip3 install -r requirements.txt
~/WormSlapBot >>> cp .env-example .env
~/WormSlapBot >>> nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
~/WormSlapBot >>> python3 main.py

# Windows
~/WormSlapBot >>> python -m venv venv
~/WormSlapBot >>> venv\Scripts\activate
~/WormSlapBot >>> pip install -r requirements.txt
~/WormSlapBot >>> copy .env-example .env
~/WormSlapBot >>> # Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
~/WormSlapBot >>> python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/WormSlapBot >>> python3 main.py --action (1/2)
# Или
~/WormSlapBot >>> python3 main.py -a (1/2)

# 1 - Создает сессию
# 2 - Запускает кликер
```
