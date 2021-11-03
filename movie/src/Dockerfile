FROM node:16-alpine
EXPOSE 8181
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY . .
ENTRYPOINT [ "node", "server.js" ]