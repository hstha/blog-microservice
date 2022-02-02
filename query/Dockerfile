FROM node:alpine

WORKDIR /home/query

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
