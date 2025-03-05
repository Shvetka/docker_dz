FROM nginx:latest
WORKDIR /etc/project
COPY index.html /usr/share/nginx/html/
COPY default.conf /etc/nginx/config/default.conf
RUN apt-get update && apt-get install -y curl
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
