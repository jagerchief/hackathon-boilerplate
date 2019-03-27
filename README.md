# Hackathon boilerplate

This repo contains all the messy docker, dependences and frameworks stuff ready to start coding when you want to start a new project.
It comes with some frontend and backend pre-build microservices

  - [FRONT] Vue.js
  - [BACK] Flask
  - More comming soon

Once setted up, you will find empty projects in all frameworks ready to start coding your new app. 
Everything is connected and all microservices can communicate to each other so you can build a API-based app easily


## Installation

Everything runs over Docker and Docker compose, so we'll asume you've already insalled it

### Clone
```sh
git clone git@github.com:jagerchief/hackathon-boilerplate.git
cd hackathon-boilerplate
```
### Set up
Install the dependencies for Vue framework

```sh
cd docker/vue
./create
```
This will create an empty Vue project (you will be asked for entering some info)

IMPORTANT: You will need to edit vue/config/index.js file and replace
```sh
host: 'localhost'
```
for
```sh
host: '0.0.0.0'
```





### Run

```sh
cd ..
docker-compose build
docker-compose up
```
Now you are running everything in local.
The ports for the framework are:

| Framework | Port |
| ------ | ------ |
| Vue | 8080 |
| Flask | 5000 |

So you can access to desired microservice via 
```sh
http://localhost:PORT
```






## Todos

 - Add more frameworks (accepted suggestions at @jagerchief)

License
----

MIT
**Free Software, Hell Yeah!**
