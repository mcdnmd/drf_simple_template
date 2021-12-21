# Web Task Scheduler Api

## .env файл
* `POSTGRES_DB` - название базы в контенере wts_db
* `POSTGRES_USER` - имя пользователя
* `POSTGRES_PASSWORD` - пароль пользователя
* `DJANGO_ENV` - тип переменных
* `SECRET_KEY` - секретный ключ для Django
* `DEBUG` - использовать Debug или нет (0 или 1)
* `DJANGO_ALLOWED_HOSTS` - разрешенные хосты (через пробел)
* `DB_ENGINE` - тип движка бд
* `DB_DATABASE` - название бд
* `DB_USER` - имя пользователя
* `DB_PASSWORD` - пароль пользователя
* `DB_HOST` - ip адресс базы (если в контейнере, то wts_db)
* `DB_PORT` - порт базы (5432 или ной)