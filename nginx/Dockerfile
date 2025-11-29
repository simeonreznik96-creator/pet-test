FROM nginx:1.29.1-alpine

COPY index.html /usr/share/nginx/html/
COPY saitest.conf /etc/nginx/conf.d/  


EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]