FROM node:14-alpine
WORKDIR /back-end
ADD node_modules.tar.gz ./
COPY src ./src/
COPY package.json ./package.json
EXPOSE 3001
CMD [ "npm", "start" ]
