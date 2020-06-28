FROM node:alpine

ENV message='Hello'
ENV colour=red

COPY package*.json ./

RUN npm install

COPY . /app

EXPOSE 3000

CMD [ "node", "/app/app3.js" ]
