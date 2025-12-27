# MySQL Sandbox

Start

```sh
docker compose up -d
export $(cat .env)
mysql -u ${MYSQL_USER} -p${MYSQL_PASSWORD} -h 127.0.0.1 -P3306 ${MYSQL_DATABASE}
```
