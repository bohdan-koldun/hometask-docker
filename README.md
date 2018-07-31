# Docker. Nginx

Контейнер: https://hub.docker.com/r/koldunbohdan/cat-blog-nginx/ 


`sudo docker build -t cat-blog-nginx .`

`sudo docker run --name blog-nginx -d -p 8080:80 cat-blog-nginx`

`docker login` 

`sudo docker tag cat-blog-nginx koldunbohdan/cat-blog-nginx`

`sudo docker push koldunbohdan/cat-blog-nginx`


`sudo docker-compose up -d`
