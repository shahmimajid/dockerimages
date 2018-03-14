FROM node:carbon
MAINTAINER Shahmi Majid

# Create app directory
WORKDIR /home/www/app

# Install app dependencies
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD[ "npm" , "start" ]

