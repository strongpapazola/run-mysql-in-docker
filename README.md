# run-mysql-in-docker

# install docker

# run mysql
```
docker run -d --restart always  --name=mysql --env="MYSQL_ROOT_PASSWORD=password123" --publish 127.0.0.1:3306:3306 -v /var/run/mysqld/:/var/run/mysqld/ -v /root/MYSQL_DATA/alldata:/var/lib/mysql mysql
```

