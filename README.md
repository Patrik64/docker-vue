# docker-vue
base docker image for vue apps

__for development mode:__

`docker-compose up -d`

`http://localhost:8080`

__for production mode:__

`docker build -t dockerreact .`

`docker run -p 8080:80 dockerreact`

`http://localhost:8080`
