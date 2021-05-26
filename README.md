<h2 align="center">Cook Blog</h2>


### Описание проекта:
Блог шеф-повара с рецептами


### Инструменты разработки

**Стек:**
- Python >= 3.7
- Django >= 3
- sqlite3

**Как работаем:**
- Все предложения и найденные ошибки добавляются в виде Issues на GitHub всеми желающими
- Обсуждаем фичи в чатах Slack и Telegram
- Над вехами работаем в рамках Trello
- Макеты разрабатываются в Figma
- Пулреквесты по таскам предлагаются всеми желающими, в комментариях к таскам люди пишут что начали делать и когда планируют закончить.
- Пул реквесты обсуждаются командой и сливаются в мастер.

**Ссылки**:
- [git](https://github.com/almat-kst/)



## Разработка

##### 1) Сделать форк репозитория и поставить звездочку)

##### 2) Клонировать репозиторий

    git clone ссылка_сгенерированная_в_вашем_репозитории

##### 3) Создать виртуальное окружение

    python -m venv env
    
##### 4) Активировать виртуальное окружение

##### 5) В папке `DS` файл `local_settings.py-example` переименовать в `local_settings.py` и прописать конект к базе

##### 6) Выполнить команду для выполнения миграций

    python manage.py migrate
    
##### 7) Создать суперпользователя

    python manage.py createsuperuser
    
##### 8) Запустить сервер

    python manage.py runserver


## License

Copyright (c) 2021