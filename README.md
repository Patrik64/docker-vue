# docker-vue
base docker image for vue apps

__for development mode:__

`docker-compose up`

`http://localhost:8080`

__for production mode:__

`docker build -t dockervue .`

`docker run -p 8080:80 dockervue`

`http://localhost:8080`
