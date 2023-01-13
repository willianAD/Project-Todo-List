FROM node:3.14
WORKDIR /front-end
ADD node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3000
CMD [ "npm", "start" ]
