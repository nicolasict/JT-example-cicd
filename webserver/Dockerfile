FROM ubuntu:14.04
RUN apt-get update && apt-get install -y nginx curl
RUN apt-get install -y htop
RUN apt-get install -y wget
EXPOSE 80
CMD nginx -g 'daemon off;'
