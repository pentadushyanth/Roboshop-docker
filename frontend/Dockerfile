FROM nginx:1.29.4-alpine
RUN rm -rf /usr/share/nginx/html/index.html 
## RUN rm -rf /etc/nginx/nginx.conf  
##  RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/
USER nginx
CMD ["nginx", "-g", "daemon off;"]
