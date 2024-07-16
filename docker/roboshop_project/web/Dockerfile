FROM nginx
RUN rm -rf /usr/share/nginx/html/*
ADD https://roboshop-builds.s3.amazonaws.com/web.zip /usr/share/nginx/html/
RUN yum install unzip -y
RUN unzip -q /usr/share/nginx/html/web.zip
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf