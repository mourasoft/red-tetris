FROM node


WORKDIR /usr/src/app


COPY package.json .
RUN npm config set unsafe - perm true

RUN npm install

COPY . .

CMD ["npm", "run", "start"]
