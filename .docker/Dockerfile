FROM node:20

WORKDIR /app

ADD ./GH/. ./

EXPOSE 3000

RUN npm install

CMD ["npm", "start" , "&&", "npm", "run"]