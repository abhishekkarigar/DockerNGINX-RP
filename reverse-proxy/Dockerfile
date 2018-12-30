FROM nginx:latest

RUN  ["rm","-f","/etc/nginx/conf.d/default.conf"]
COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./includes/ /etc/nginx/includes/
COPY ./backend-not-found.html /var/www/html/backend-not-found.html