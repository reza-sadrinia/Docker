FROM nginx:alpine

ADD ./site /usr/share/nginx/html/




RUN rm /etc/nginx/conf.d/default.conf

ADD ./default.conf /etc/nginx/conf.d/
