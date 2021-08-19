FROM node:15

WORKDIR /use/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npx", "next"]