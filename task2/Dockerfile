FROM node:16-alpine

# создание директории образа
WORKDIR /home/ilovedocker/app

# копирование образа
COPY hello.sh ./

# скрипт в качестве команды запуска образа
ENTRYPOINT ["sh", "hello.sh"]
