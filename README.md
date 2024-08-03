# simple-telegram-bot-kit

> Nest TS  
> node-telegram-bot-api  

```txt
start - Запуск
ping - Ping
```

## Installation

```bash
make cp-env
```

##### After you must configure your app in .env file

```bash
make install
```

View docker container logs

```bash
make logs
```

## Build Setup

### Production

```bash
make
```

### Building for production

To building for production you need to change `COMPOSE_FILE` param in *.env* to *docker-compose.prod.yml* and follow the above steps

### Development

```bash
make dev
```
