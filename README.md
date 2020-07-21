# devops

docker run mysql

docker run --name mysql8 -v /var/config/mysql:/etc/mysql -v /var/data/mysql:/var/lib/mysql -v /var/run/mysql:/var/run/mysql -v /var/log/mysql:/var/log/mysql -e MYSQL_ROOT_PASSWORD=1wicZsdT1TfmPwId -d mysql:8.0
