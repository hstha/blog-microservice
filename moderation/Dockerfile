FROM node:alpine

WORKDIR /home/moderation

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
