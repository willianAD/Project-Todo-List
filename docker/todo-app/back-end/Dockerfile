FROM alpine:3.17.1
WORKDIR /back-end
ADD node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3001
CMD [ "npm", "start" ]
