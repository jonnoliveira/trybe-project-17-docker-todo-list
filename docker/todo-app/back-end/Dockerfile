FROM node:14.21.2-alpine3.17
WORKDIR /back-end
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]
