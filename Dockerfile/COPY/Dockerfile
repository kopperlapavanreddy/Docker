FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/htm/index.html
COPY index.html /usr/share/nginx/htm/
CMD ["nginx", "-g", "daemon off;"]