FROM node:latest

MAINTAINER Dani Jimenez <dani.jimenez@waynabox.com>

WORKDIR /server

RUN apt-get install -y git
RUN npm install -g sails grunt-cli grunt bower nodejs pm2 npm-check-updates


# Expose ports.
EXPOSE 1337

CMD ["sails", "lift"]

