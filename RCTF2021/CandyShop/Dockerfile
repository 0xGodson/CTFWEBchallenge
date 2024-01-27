FROM node:21.6.0-alpine3.19

COPY src /app
COPY flag /flag

RUN cd /app && npm update -g && npm install && adduser meow -D

USER meow

CMD cd /app && node app.js