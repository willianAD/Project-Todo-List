FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
ADD node_modules.tar.gz ./
COPY ./ ./
# EXPOSE 3000
CMD [ "npm", "start" ]
