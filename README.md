# Docker Nginx Set up

start container

- run command `docker-compose up -d`

stop container

- run command `docker-compose stop`

rebuild (image) & run container

- run command `docker-compose up -d --build`

change nginx configuration (reverse proxy, whatever you want)

- /nginx/conf.d/default.conf

access subdomain as localhost (alternative)

- lvh.me:port

## how to access subsite

- access subsite www -> `localhost`
- access subsite kbank -> `kbank.localhost`
- access subsite tasco -> `tasco.localhost`
- access subsite lando -> `lando.localhost`
