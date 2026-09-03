FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /tmp/user/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/dockerfiles/refs/heads/main/ADD/Dockerfile /tmp/user/nginx/html/index.html
RUN chomd +r /tmp/user/nginx/html/index.html
RUN sample.tar /tmp/
CMD ["nginx", "-g", "daemon-off;"]