# define base image
FROM node:alpine

COPY ./package.json ./
COPY ./index.js ./

# install some dependencies
RUN npm install

# Default command
CMD ["npm", "start"]
