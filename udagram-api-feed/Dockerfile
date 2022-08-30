FROM node:latest

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm ci

COPY . /usr/src/app/

EXPOSE 8080
CMD [ "npm", "run", "prod" ]
