FROM node:16-alpine

WORKDIR /usr/mern-nginx-docker/app/backend

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]
