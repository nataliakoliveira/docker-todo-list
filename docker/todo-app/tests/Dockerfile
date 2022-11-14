FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/tests

COPY node_modules.tar.gz .

COPY . .

RUN npm test

CMD ["npm", "test"]