FROM node:0.10.36-onbuild
ENV REDIS_HOST redis
ENV REDIS_PORT 6379
WORKDIR /app
COPY package.json .
RUN npm install
copy . /app
EXPOSE 3000
CMD [ "npm", "start" ]
