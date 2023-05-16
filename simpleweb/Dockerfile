# Specify base image
FROM node:14-alpine

#include a new working directory
WORKDIR /usr/app

#copy file systems
COPY ./ ./

#Install dependencies
RUN npm install 

#Default cmd
CMD ["npm","start"]



