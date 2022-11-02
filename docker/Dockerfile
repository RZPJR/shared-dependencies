FROM nginx:1.23-alpine

WORKDIR /var/www/html/dist

COPY nginx/apps.conf /etc/nginx/conf.d/apps.conf
COPY nginx/nginx.conf /etc/nginx/nginx.conf
COPY importmap.json .

CMD ["nginx", "-g", "daemon off;"]
