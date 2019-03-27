FROM node:latest

MAINTAINER Dani Jimenez <dani.jimenez@waynabox.com>

WORKDIR /app

RUN npm --user root --unsafe-perm true install npm -g

RUN npm install -g --silent \
    yarn \
    create-react-app@1.5.2

EXPOSE 3000

CMD ["yarn", "start"]
