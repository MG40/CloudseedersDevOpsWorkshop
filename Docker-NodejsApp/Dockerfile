FROM node:12.0-slim
WORKDIR /app
COPY package*.json ./
RUN npm install express --save
COPY . .
EXPOSE 3000
CMD [ "node", "index.js" ]
