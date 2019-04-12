FROM nginx:1.15.11
RUN apt update && apt install -y lsof procps curl
COPY nginx.conf /etc/nginx/nginx.conf