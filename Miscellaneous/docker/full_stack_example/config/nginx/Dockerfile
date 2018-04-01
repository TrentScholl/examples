FROM nginx:1.13-alpine
RUN apk add --no-cache curl
HEALTHCHECK CMD curl -f http://localhost/server-status
COPY ./nginx.conf /etc/nginx/