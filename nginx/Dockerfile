FROM nginx:alpine

LABEL maintainer="robertoh89@gmail.com"

RUN rm /etc/nginx/conf.d/default.conf

COPY conf/flask.conf /etc/nginx/conf.d/flask.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx"]