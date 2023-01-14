FROM node:14-alpine
WORKDIR /front-end
ADD node_modules.tar.gz ./
COPY src ./src/
COPY public ./public/
COPY package.json ./package.json
EXPOSE 3000
CMD [ "npm", "start" ]
