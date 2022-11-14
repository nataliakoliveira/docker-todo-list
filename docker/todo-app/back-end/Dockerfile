FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

COPY node_modules.tar.gz .

COPY . .

CMD "npm", "start"