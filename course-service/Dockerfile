FROM node:14

# App directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

# use port on docker
EXPOSE 8080

CMD [ "node", "index.js"]