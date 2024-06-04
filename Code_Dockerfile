# Docker_image_creation
Created a Docker file and Hosted a Calculator which is build by React and Node-js 

# Code inside Dockerfile.

FROM node:22-alpine3.19
WORKDIR /Docker/Changes/
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3003
CMD [ "npm","start"]

# Hosted the Calculator on 3003 - Localhost
