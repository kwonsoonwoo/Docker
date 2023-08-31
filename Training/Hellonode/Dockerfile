FROM node:16-alpine

COPY    ./package* /usr/src/app/
WORKDIR /usr/src/app
RUN     npm install

COPY . /usr/src/app

EXPOSE 8080
CMD    node server.js
