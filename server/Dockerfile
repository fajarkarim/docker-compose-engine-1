FROM node:8
MAINTAINER Fajar Abdul Karim
WORKDIR /usr/src/app
COPY package.json ./
RUN yarn install
COPY . .
EXPOSE 8080
CMD ["yarn", "start"]