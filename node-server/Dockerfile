FROM node:23-alpine3.20

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app/

EXPOSE 3000

CMD ["node", "main.js"]
