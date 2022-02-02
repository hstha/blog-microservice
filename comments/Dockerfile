# microservice/blog/comments
FROM node:alpine

WORKDIR /home/comments

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
