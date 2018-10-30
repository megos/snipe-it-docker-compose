# snipe-it-docker-compose
docker-compose for snipe-it

## Setup

1. Create APP_KEY

```
$ docker-compose run --rm app
Please re-run this container with an environment variable $APP_KEY
An example APP_KEY you could use is:
[YOUR APP_KEY (notice: contains base64:)]

$ docker-compose down
```

2. Set environment in `docker-compose.yml`
    - APP_KEY
    - APP_URL
    - MAIL_FROM_ADDR
    - MAIL_REPLYTO_ADDR
    - maildomain
    
3. Up 

```
$ docker-compose up -d
```
