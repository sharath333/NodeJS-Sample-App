FROM node:0.10.40

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY ./app/ ./
RUN npm install

CMD ["node", "app.js"]