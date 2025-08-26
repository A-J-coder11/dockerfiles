FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://safebox.life/
CMD ["nginx", "-g", "daemon off;"]