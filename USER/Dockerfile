FROM almalinux:9
RUN dnf install nginx -y
RUN useradd raghu

USER raghu
CMD ["google.com"]
ENTRYPOINT ["ping"]
