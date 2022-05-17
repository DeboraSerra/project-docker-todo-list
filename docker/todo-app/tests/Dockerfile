FROM mjgargani/puppeteer:trybe1.0 AS todotest
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
CMD [ "npm", "test" ]
