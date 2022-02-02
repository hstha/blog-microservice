# microservice/blog/client
FROM node:alpine

WORKDIR /home/client

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
