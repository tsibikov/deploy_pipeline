FROM debian:latest
RUN apt-get update && apt-get install -y nginx
RUN apt-get update && apt-get install -y python3
COPY nginx.conf /etc/nginx/conf.d
CMD ["nginx", "-g", "daemon off;"]
RUN apt install python3-pip -y
RUN apt install supervisor -y