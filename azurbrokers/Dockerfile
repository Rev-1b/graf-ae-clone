FROM nginx:stable-alpine

COPY ./azurbrokers/azurbrokers.html /usr/share/nginx/html/index.html
COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]