# Docker for Python3.9, Django3.0

## Get Start

### docker run

```
docker-compose build
docker-compose run --rm web django-admin.py startproject [project name] .
```

### edit setting.py

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres',
        'PASSWORD': 'postgres',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```

### start new app

```
# python manage.py startapp [app name]
// inside docker container
```
