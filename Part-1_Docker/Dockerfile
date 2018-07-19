
FROM dev_web_task:v1.1
MAINTAINER devops@gmail.com
EXPOSE 80:80

COPY nginx.conf /usr/local/nginx/conf/
COPY httpd.conf /etc/httpd/conf/
COPY .htpasswd  /etc/httpd/

COPY service_start.sh /

ENTRYPOINT "/service_start.sh" && /bin/bash
