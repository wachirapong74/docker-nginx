FROM nginx:1.16.0-alpine

# Update library
RUN apk update

# Install packages
RUN apk add vim wget unzip git zip curl
RUN apk add htop

# expose port 80
EXPOSE 80

# expose port 443
EXPOSE 443