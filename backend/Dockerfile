FROM node:lts

WORKDIR /app

COPY package.json package-lock.json* ./
RUN npm install

COPY src ./

ENV PORT=3000

EXPOSE 3000

CMD ["node", "server.js"]