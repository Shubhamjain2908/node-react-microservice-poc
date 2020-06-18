FROM node:alpine

WORKDIR /usr/posts
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]