# define base image
FROM node:alpine

WORKDIR /usr/app
COPY ./package.json /usr/app

# install some dependencies
RUN npm install

# copy source files to the application folder.
COPY ./index.js /usr/app

# Default command
CMD ["npm", "start"]
