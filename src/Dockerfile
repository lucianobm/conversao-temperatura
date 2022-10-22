FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
# no final do server.js tem a porta utilizada
CMD ["node", "server.js"]
