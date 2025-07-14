FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
# removing default nginx html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
# copying to above path as per documentation
ADD static /usr/share/nginx/html/
# Adding static files to above path 