FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/app

ADD ./node_modules.tar.gz ./

COPY . .

CMD [ "npm", "test" ]
