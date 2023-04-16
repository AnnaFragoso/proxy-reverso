# specify the node base image with your desired version node:<version>
FROM node:16.3.0-alpine

WORKDIR /usr/src/app

RUN apk add nodejs && apk add npm --no-cache

COPY package*.json ./

RUN npm install

COPY . .

# replace this with your application's default port
EXPOSE 4000

CMD ["node", "index.js"]