FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /tmp/user/nginx/html/index.html 
COPY index.html /tmp/user/nginx/html
CMD ["nginx", "-g", "daemon-off,"]
