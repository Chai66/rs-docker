FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
# removing default nginx html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
# copying to above path as per documentation
ADD static /usr/share/nginx/html/
# Adding static files to above path 