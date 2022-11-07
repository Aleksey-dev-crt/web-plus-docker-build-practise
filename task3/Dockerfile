FROM node:16-alpine

# создание директории образа
WORKDIR /home/ilovedocker/app

# копирование packege.json и package-lock.json
COPY /packages/package*.json ./

# установка зависимостей
RUN npm i

# копирование исходного кода
COPY ./src ./

# используемый порт
EXPOSE 3032

# скрипт в качестве команды запуска приложения
CMD ["node", "main.js"]
