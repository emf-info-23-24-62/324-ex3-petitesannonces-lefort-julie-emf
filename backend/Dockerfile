FROM node:18-alpine
 
WORKDIR /usr/src/app
 
COPY package.json ./
RUN npm install
 
COPY . .
 
WORKDIR /usr/src/app/src
 
CMD ["node", "server.js"]