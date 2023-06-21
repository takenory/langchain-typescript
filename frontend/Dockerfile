FROM node:18.16.0-alpine
WORKDIR /usr/src/app
COPY . /usr/src/app

RUN npm cache clear --force && npm install
