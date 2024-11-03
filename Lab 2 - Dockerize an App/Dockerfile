FROM node:20-alpine

WORKDIR /usr/src/app

COPY app/package.json ./
COPY app/app.js ./
COPY app/views ./views

RUN npm install

EXPOSE 5000

ENTRYPOINT ["node", "app.js"]