FROM mjgargani/puppeteer:trybe1.0 AS todotest
WORKDIR /app
COPY . .
RUN npm install
CMD [ "npm", "test" ]
