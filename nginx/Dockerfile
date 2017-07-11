FROM nginx:1.13

RUN rm /etc/nginx/conf.d/*.conf

COPY ./ssl/* /etc/nginx/ssl/
COPY ./common-ssl.conf /etc/nginx/
COPY ./sites/*.conf /etc/nginx/conf.d/
