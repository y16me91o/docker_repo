FROM nginx
RUN rm -rf /usr/share/nginx/html/*
ADD web.tar.gz /usr/share/nginx/html/
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf