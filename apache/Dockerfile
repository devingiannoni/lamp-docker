FROM httpd:2.4.33-alpine
RUN apk update;\
    apk upgrade;
COPY apache.conf /usr/local/apache2/conf/apache.conf
RUN echo "Include /usr/local/apache2/conf/apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf
RUN mkdir -p /var/www/html