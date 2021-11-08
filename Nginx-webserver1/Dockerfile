FROM nginx:latest

RUN apt update && apt upgrade -y

COPY ./index.html /usr/share/nginx/html/index.html

EXPOSE 8081:80