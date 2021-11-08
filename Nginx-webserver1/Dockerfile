FROM nginx:latest

RUN apt update && apt upgrade -y

COPY ./index.html /usr/share/nginx/html/index.html
COPY ./nginx.conf /etc/nginx/nginx.conf