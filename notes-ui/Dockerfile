FROM node:10.19.0

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm build

EXPOSE 3000

CMD ["npm", "start"]
