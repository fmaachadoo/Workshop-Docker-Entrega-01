FROM node:16

WORKDIR /users-service

COPY . /users-service/

RUN yarn

COPY . /users-service/

EXPOSE 7101

CMD yarn watch