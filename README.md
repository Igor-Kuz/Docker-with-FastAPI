# Repository with examples of dockerizing FastAPI project with traefik server. 


### In this project were used:
- fastapi
- psycopg2-binary
- ormar
- uvicorn
- Docker
- Docker-Compose

### Инструменты разработки
 
**Стек:**

- fastapi==0.63.0
- asyncpg==0.22.0
- ormar==0.10.5
- psycopg2-binary==2.8.6
- uvicorn==0.13.4


## Установка и запуск

##### 1) Открыть терминал или консоль и перейти в нужную Вам директорию

##### 2) Клонировать репозиторий и поставить звездочку)

    git clone https://github.com/Igor-Kuz/Docker-with-FastAPI

##### 3) Создать виртуальное окружение

    python -m venv venv
    
##### 3) Создать образ
    docker-compose build


##### 4 ) Запустить контейнер

    docker-compose up -d


##### 6) Запустить с прод настройками

    docker-compose -f docker-compose.prod.yml up -d --build