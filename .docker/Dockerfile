FROM node:20

WORKDIR /app

ADD ./GH/. ./

EXPOSE 8080

RUN npm install

CMD ["npm", "start" , "&&", "npm", "run"]