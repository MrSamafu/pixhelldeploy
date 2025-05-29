FROM node:current-alpine3.21

RUN npm i pm2 -g

RUN apk update && \
    apk add --update git

RUN git clone https://github.com/MrSamafu/apipix.git

WORKDIR /apipix

RUN npm install

EXPOSE 3000
CMD pm2-runtime start index.js --name apipix