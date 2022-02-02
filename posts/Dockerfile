FROM node:alpine

WORKDIR /home/posts

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
