FROM node:20.5-alpine

WORKDIR  /app

COPY package.json .

RUN npm i -g @nestjs/cli

RUN npm install

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "npm", "run", "start:dev"]