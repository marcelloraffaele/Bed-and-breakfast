FROM nginx:alpine

LABEL maintainer="Raffaele Marcello <example@example.com>"

COPY default.conf /etc/nginx/conf.d
COPY html/ /usr/share/nginx/html/

EXPOSE 8080

STOPSIGNAL SIGTERM

CMD ["nginx", "-g", "daemon off;"]