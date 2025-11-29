FROM nginx:1.29.1-alpine

COPY index.html /usr/share/nginx/html/

COPY saitest.conf /etc/nginx/conf.d/

COPY ssl/ /etc/nginx/ssl/

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]