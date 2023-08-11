FROM betrybe/puppetter:1.0

WORKDIR /app/tests/

COPY package*.json ./

ADD ./node_modules.tar.gz ./

RUN npm i

COPY . ./

ENTRYPOINT [ "npm" ]

CMD [ "test" ]

