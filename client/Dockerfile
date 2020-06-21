FROM node:alpine

# bug solve for create-react-app 
ENV CI=true

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]