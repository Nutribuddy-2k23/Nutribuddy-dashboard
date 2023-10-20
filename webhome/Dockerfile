FROM nginx

RUN apt-get update && apt-get upgrade -y

WORKDIR /usr/share/nginx/html

COPY assets/ ./assets/

COPY * ./

EXPOSE 3000

CMD ["nginx", "-g", "daemon off;"]