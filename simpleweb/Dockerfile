#specify a base Image
FROM node:alpine

#install some dependencies
WORKDIR /usr/app
COPY ./package.json /usr/app
RUN npm install
COPY ./ /usr/app
 

#default command
CMD ["npm", "start"]