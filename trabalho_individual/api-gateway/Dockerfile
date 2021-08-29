FROM node:16

WORKDIR /api-gateway

COPY . /api-gateway/

RUN yarn

COPY . /api-gateway/

EXPOSE 7000

CMD yarn watch