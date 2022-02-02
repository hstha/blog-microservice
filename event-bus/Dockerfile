# microservice/blog/event-bus
FROM node:alpine

WORKDIR /home/event-bus

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
