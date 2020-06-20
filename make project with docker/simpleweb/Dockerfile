# Specify base Image
# node:alpine is already created and get from docket hub.
FROM node:alpine

WORKDIR /usr/app

#COPY project file to docker container
# Add dependencies

COPY ./package.json ./
RUN npm install 
COPY ./ ./

# Default command
CMD ["npm","start"]