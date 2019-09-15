# Pulling the base image
FROM alpine

# settingup the Working Directory
WORKDIR '/user/app'

# Preperation of the Docker image
COPY ./package.json ./
RUN install npm
COPY ./ ./ 

# Command
CMD ["npm" ,  "start"]

