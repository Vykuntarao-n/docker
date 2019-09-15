# Base Image
FROM node:alpine

# Setting up the working Directory
WORKDIR '/app'

# Prepare the image
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Docker command to start the container
CMD ["npm" , "start" ]

