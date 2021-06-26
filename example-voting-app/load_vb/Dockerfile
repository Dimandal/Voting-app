FROM ubuntu:latest

MAINTAINER Dibyendu

RUN apt-get update && apt-get install nginx -y

RUN rm /etc/nginx/sites-available/default

COPY default.conf /etc/nginx/sites-available/default

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
