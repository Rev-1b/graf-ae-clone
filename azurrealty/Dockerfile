FROM nginx:stable-alpine

COPY ./azurrealty/azurrealty.html /usr/share/nginx/html/index.html
COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]