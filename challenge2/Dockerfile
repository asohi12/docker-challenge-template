# Use the official Node.js image from the Docker Hub
FROM node:latest

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# Expose port and start application
EXPOSE 8080
CMD [ "node", "server.js" ]
