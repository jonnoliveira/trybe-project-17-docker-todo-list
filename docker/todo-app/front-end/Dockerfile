FROM node:14.21.2-alpine3.17
EXPOSE 3000
ADD node_modules.tar.gz .
WORKDIR /todo-app/front-end
COPY . .
CMD [ "npm start" ]
