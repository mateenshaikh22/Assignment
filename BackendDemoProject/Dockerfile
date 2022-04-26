FROM node

WORKDIR /app

COPY package.json .

RUN npm install

ADD . .

EXPOSE 80

CMD ["node", "app.js"]