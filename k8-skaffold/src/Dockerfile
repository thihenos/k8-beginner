FROM node:10.18.0-alpine3.10

MAINTAINER @thihenos

RUN apk update

RUN apk add curl

COPY app/ usr/app

WORKDIR usr/app

EXPOSE 3000

RUN npm install

CMD ["npm","start"]
