FROM node:14

WORKDIR /app/MyLists-Backend  

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["node", "index.js"] 