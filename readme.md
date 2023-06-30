# VKInder
## Описание приложения
VKInder - небольшой бот, написанный на Python, позваляющий искать тебе собеседников противоположного пола твоего возраста из твоего города :)

## Использование 
### Требования
* Python3.10 или выше
* PostgreSQL
### Установка

Linux:
```
git clone https://github.com/chilya02/VKInder.git
```
### Настройка
Файл `bot_config.py`:
```Python
VK_LOGIN = ''    #Номер телефона аккаунта в вк
VK_PASSWORD = '' #Пароль аккаунта в вк

TWO_FACTOR_AUTHENTICATION = True

API_TOKEN = ''  #Токен группы
GROUP_ID = ''   #Идентификатор группы
```

Файл `bot_db/db_config/py`:
```Python
DB_NAME = ''            #Название БД
DB_HOST_NAME = ''       #Сервер БД
DB_USER = ''            #Пользователь БД
DB_USER_PASSWORD = ''   #Пароль пользователя БД
```
