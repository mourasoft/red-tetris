FROM node:alpine

WORKDIR /usr/src/app

COPY package.json .


RUN npm i -g @nestjs/cli
RUN npm config set unsafe - perm true
RUN npm install


COPY . .



CMD ["npm", "run", "start:dev"]
