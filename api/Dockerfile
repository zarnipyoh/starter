FROM node:carbon

# Create app directory
WORKDIR /app

# --dev--
RUN npm install -g nodemon

# Install app dependencies
COPY package*.json ./
RUN npm install

EXPOSE 8080
CMD [ "node", "server.js" ]
