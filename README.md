# fastapi-bookcrossing
Проект по разработке сервиса для обмена книгами между пользователями с использованием FastAPI, Redis и асинхронности.

В данном проекте были разработаны и объединены два сервиса на языке Python:

- Сервис по обмену книгами из персональных библиотек с другими пользователями с использованием FastAPI WEB фреймворка **Bookcrossing App**.

  [Репозиторий](https://github.com/EvaSamoilenko/fastapi-bookcrossing/tree/main/app)
  [Документация](https://evasamoilenko.github.io/fastapi-bookcrossing/bookrossing_app/)
  
- Программа парсинга книг по заданной ссылке **Parser App** при помощи библиотек async и BeautifulSoup. Настройка асинхронного парсинга с Redis и Celery. Интеграция двух приложений.
  
  [Репозиторий](https://github.com/EvaSamoilenko/fastapi-bookcrossing/tree/main/parser)
  [Документация](https://evasamoilenko.github.io/fastapi-bookcrossing/parser_app/)

В процессе работы были использованы такие **технологии**, как:

- FastAPI, SQLAlchemy, PostgreSQL,
- http, OAuth2,
- BeautifulSoup, asyncio, aiohttp,
- Docker, Celery, Redis.

**[Документирование](https://evasamoilenko.github.io/fastapi-bookcrossing/)** производилось с помощью языка разметки MarkDown и генератора сайтов MkDocs, которые задеплоены на отдельной ветке и всегда доступны. В документации присутствуют описания API, интеграции, расширенные комментарии эндпоинтов и скриншоты работы сервисов.
