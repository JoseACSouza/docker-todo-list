FROM node:16-alpine

EXPOSE 3000

WORKDIR /app/front-end/

COPY package*.json ./

ADD ./node_modules.tar.gz ./

RUN npm i

COPY . ./

ENTRYPOINT [ "npm" ]

CMD [ "start" ]

