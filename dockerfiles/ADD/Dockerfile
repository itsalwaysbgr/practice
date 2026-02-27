FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/notes/main/github-actions-1.txt /usr/share/nginx/html/index.html
EXPOSE 80
cmd ["nginx", "-g", "daemon off;"]