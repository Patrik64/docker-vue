# docker-vue
base docker image for vue apps

## Usage:

__for development mode:__

`docker-compose up`

open the browser and navigate to:

`http://localhost:8080`

__for production mode:__

`docker build -t dockervue .`

`docker run -p 8080:80 dockervue`

open the browser and navigate to:

`http://localhost:8080`

## Features:

- running in development mode runs the unit tests and starts the dev server
- changing the code outside of the container is reflected immediatelly with hot reload
- the production mode creates a production build that is served using nginx 
- to only run the tests use `docker-compose run tests`
