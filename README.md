```sh
export $(cat .env)
mysql -u ${MYSQL_USER} -p${MYSQL_PASSWORD} -h 127.0.0.1 -P3306 ${MYSQL_DATABASE}
```
