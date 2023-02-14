FROM node:14.21.2-alpine3.17
WORKDIR /front-end
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]
