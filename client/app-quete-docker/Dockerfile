# Dockerfile
FROM node:current-alpine3.10

RUN mkdir /client/app-quete-docker
WORKDIR /client/app-quete-docker
COPY package*.json ./

RUN npm i

COPY src src
COPY public public

CMD npm start