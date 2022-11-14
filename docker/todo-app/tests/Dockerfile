FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/tests

EXPOSE 3001

COPY node_modules.tar.gz .

COPY . .

RUN npm test

CMD "npm", "test"