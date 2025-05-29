FROM node:current-alpine3.21
RUN apk update && \
    apk add --update git

RUN git clone https://github.com/MrSamafu/pixhelldb.git

WORKDIR /pixhelldb

RUN npm install

EXPOSE 5173

CMD npm run dev -- --host 0.0.0.0