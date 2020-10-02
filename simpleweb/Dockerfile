#specify base image
FROM node:alpine

#create working directory
WORKDIR /usr/app

#copy files from working directory
COPY ./package.json ./

#install some dependencies
RUN npm install
COPY ./ ./

#default command
CMD ["npm", "start"]
