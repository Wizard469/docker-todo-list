FROM node:14

WORKDIR /usr/src/app

EXPOSE 3001

ADD ./node_modules.tar.gz ./

COPY . .

CMD [ "npm", "start" ]
