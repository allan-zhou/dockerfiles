# docker nginx
- mode 1
docker run --name demo-nginx -p 80:80 -v /home/zhoujl/src/mysrc/angular/angular-demo/dist:/usr/share/nginx/html:ro -d nginx

- mode 2
docker build -t popzhou/nginx .
docker run --name demo-nginx -p 80:80 -d popzhou/nginx


docker run --name demo-nginx -p 80:80 -v /home/zhoujl/src/mysrc/angular/angular-demo/dist:/etc/nginx/nginx.conf:ro -d popzhou/nginx



