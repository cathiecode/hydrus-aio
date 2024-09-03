## Certbot new cert
```
docker compose run --entrypoint certbot certbot certonly --email email@example.com --webroot -w /var/lib/letsencrypt/ -d domain.tld
```
