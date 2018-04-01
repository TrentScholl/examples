FROM httpd:2.4-alpine
RUN apk add --no-cache curl
HEALTHCHECK CMD curl -f http://localhost
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf