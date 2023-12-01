FROM node:21.2-alpine3.18

COPY src /app
COPY flag /flag

RUN cd /app && npm update -g && npm install && adduser meow -D

USER meow

CMD cd /app && node app.js