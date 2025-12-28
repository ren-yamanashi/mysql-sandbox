# MySQL Sandbox

Start

```sh
docker compose up -d
mysql -u ${mysql_user} -p -h 127.0.0.1 -P3306
```

Seed

```sh
mysql -u ${mysql_user} -p -h 127.0.0.1 -P3306 < src/world.sql
```
