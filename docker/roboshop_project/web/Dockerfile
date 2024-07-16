FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN curl -o /tmp/web.zip https://roboshop-builds.s3.amazonaws.com/web.zip
ADD /tmp/web.zip /usr/share/nginx/html/
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf 