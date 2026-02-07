FROM nginx:latest


RUN apt update && apt -y install iputils-ping curl


COPY nginx.conf /etc/nginx/nginx.conf


EXPOSE 8080
