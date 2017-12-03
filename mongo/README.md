# docker mongodb


- [dockerfile命令 中文解释](http://www.zslin.com/web/article/detail/59)
- [docderfile命令 官方解释](https://docs.docker.com/engine/reference/builder/#volume)
- [docker build命令 官方解释](https://docs.docker.com/engine/reference/builder/#volume)
- [dockerfile project --mongo](https://github.com/dockerfile/mongodb/blob/master/Dockerfile#L21)
- [install-mongodb-on-ubuntu](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)


# docker build
docker build -t popzhou/mongo .

# docker run 
docker run --name mongodb -p 127.0.0.1:27017:27017 -d popzhou/mongo 