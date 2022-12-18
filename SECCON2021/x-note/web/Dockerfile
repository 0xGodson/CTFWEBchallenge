FROM node:17.5.0-slim
ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json", "package-lock.json", "./"]

RUN npm install --production

COPY . .

CMD ["node", "--no-deprecation", "index.js"]
