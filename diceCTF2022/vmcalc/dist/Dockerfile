FROM node:16.20.2-bullseye-slim
    
RUN mkdir -p /app

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

USER node

CMD ["node", "index.js"]