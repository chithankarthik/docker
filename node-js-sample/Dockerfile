#Installing latest nodejs application package
FROM node:4

#Changing working directory as /app
WORKDIR /app

#pakage.json file have the application
COPY package*.json .

#Building modules
RUN npm install

COPY . /app

EXPOSE 5000

CMD [ "npm", "start" ]
