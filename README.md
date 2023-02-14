# prestashop-docker-compose

```bash
docker network create prestashop-network
```

```bash
find . -type f -exec chmod 644 {} \; && find . -type d -exec chmod 755 {} \;
```

```bash
php index_cli.php --db_server=prestashop-mysql --db_name=prestashop --db_user=root --db_password=root --email="email@example.com" --password=123123123 --newsletter=0 --country=nl --domain=127.0.0.1:8080 --name=Test
```