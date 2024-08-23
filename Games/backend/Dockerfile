FROM node

WORKDIR /app

COPY package.json .

COPY . .

RUN npm install

EXPOSE 4000

ENTRYPOINT ["npm", "start"]