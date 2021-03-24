FROM node:13-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "node", "src/index.js" ]
