FROM node:3.14
WORKDIR /back-end
ADD node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3001
CMD [ "npm", "start" ]
