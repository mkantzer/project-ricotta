FROM node:13-alpine

WORKDIR /usr/src/app/server-api

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8001

CMD ["npm", "start"]