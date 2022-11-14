FROM node:14-alpine

WORKDIR /app


COPY node_modules.tar.gz .

COPY . .

RUN npm start

CMD ["npm", "start"]