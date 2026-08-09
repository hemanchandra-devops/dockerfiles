FROM almalinux:9
RUN dnf install nginx -y
RUN useradd heman

USER heman
CMD ["nginx", "-g", "daemon off;"]