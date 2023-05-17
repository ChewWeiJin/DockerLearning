# Specify base image
FROM node:14-alpine

#include a new working directory
WORKDIR /usr/app

#copy file systems
COPY ./package.json ./

#Install dependencies
RUN npm install 

COPY ./ ./

#Default cmd
CMD ["npm","start"]



