FROM nginx:alpine

RUN rm -f /etc/nginx/conf.d/default.conf
ADD conf/default.conf /etc/nginx/conf.d/default.conf
ADD conf/nginx.conf /etc/nginx/nginx.conf

ADD src/index.html /var/www/index.html