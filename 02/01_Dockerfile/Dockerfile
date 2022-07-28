FROM ubuntu:18.04
RUN apt-get update \
&& apt-get install -y nginx \
&& rm -rf /var/lib/apt/lists/*
COPY index.html /var/www/html/
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
