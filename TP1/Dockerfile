FROM node:10

WORKDIR /usr/src/app

COPY ./wik-njs-303-skeleton ./

RUN npm install

COPY . .

EXPOSE 8080
CMD ["node", "app.js"]
