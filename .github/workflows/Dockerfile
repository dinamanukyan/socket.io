FROM node:18

WORKDIR /app

COPY package*.json /

RUN npm install

COPY . .

EXPOSE 9007

CMD [ "npm", "start"]
