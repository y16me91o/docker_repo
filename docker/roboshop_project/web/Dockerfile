FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN curl -o /tmp/web.zip https://roboshop-builds.s3.amazonaws.com/web.zip
RUN cd /usr/share/nginx/html
RUN unzip /tmp/web.zip
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf 