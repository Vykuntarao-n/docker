# Pulling the base image
FROM node:alpine

# settingup the Working Directory
WORKDIR '/user/app'

# Preperation of the Docker image
COPY ./package.json ./
RUN npm install
COPY ./ ./ 

# Command
CMD ["npm" ,  "start"]

