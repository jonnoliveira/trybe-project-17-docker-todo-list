FROM node:14.21.2-alpine3.17
EXPOSE 3001
ADD node_modules.tar.gz .
WORKDIR /todo-app/back-end
COPY . .
CMD [ "npm start" ]
