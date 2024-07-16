FROM nginx
RUN rm -rf /usr/share/nginx/html/*
ADD https://roboshop-builds.s3.amazonaws.com/web.zip /usr/share/nginx/html/
RUN apt install unzip -y
RUN unzip /usr/share/nginx/html/web.zip
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf