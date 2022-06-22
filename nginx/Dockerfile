FROM ubuntu

RUN apt-get update
RUN apt-get install -y nginx
RUN apt-get install -y nginx-extras

COPY nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-g", "daemon off;"]