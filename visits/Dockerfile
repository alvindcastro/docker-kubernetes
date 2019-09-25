# Use an exisiting docker image as a base
FROM node:alpine

WORKDIR /app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Tell the image what to do when it starts as a container
CMD ["npm", "start"]