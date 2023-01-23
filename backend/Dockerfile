FROM node:18-alpine3.17

WORKDIR /app

COPY package.json ./

RUN npm install

RUN npm run build

COPY . .

CMD ["npm", "run", "start"]
