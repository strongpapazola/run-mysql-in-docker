# run-mysql-in-docker

# install docker

# run mysql
```
docker run -d --restart always  --name=mysql --env="MYSQL_ROOT_PASSWORD=password123" --publish 127.0.0.1:3306:3306 -v /var/run/mysqld/:/var/run/mysqld/ -v /root/MYSQL_DATA/alldata:/var/lib/mysql mysql
```

# install mariadb client
```
sudo apt-add-repository 'deb [arch=amd64,arm64] http://mariadb.mirror.liquidtelecom.com/repo/10.5/ubuntu focal main'
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com F1656F24C74CD1D8
apt update
apt install mariadb-client-10.5 mariadb-client-core-10.5
```
