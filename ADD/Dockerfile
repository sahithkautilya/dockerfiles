FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-84s/dockerfiles/tree/main/COPY/qi /usr/share/nginx/html/
RUN chmod +r /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]