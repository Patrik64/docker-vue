# docker-vue
base docker image for vue apps

for development mode:

docker-compose up -d

http://localhost:3000

for production mode:

docker build -t dockerreact .

docker run -p 8080:80 dockerreact

http://localhost:8080
