# Docker Nginx Set up

start container
- run command "docker-compose up -d"

stop container
- run command "docker-compose stop"

rebuild (image) & run container
- run command "docker-compose up -d --build"

change configuration nginx (reverse proxy, whatever you want)
- /nginx/conf.d/default.conf

access subdomain as localhost (alternative)
- lvh.me:port
