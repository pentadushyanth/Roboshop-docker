FROM nginx:1.29.4-alpine
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/