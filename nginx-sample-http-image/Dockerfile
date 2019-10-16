FROM nginx:1.17
EXPOSE 80
CMD ["/bin/bash","-c","date > /usr/share/nginx/html/index.html && exec nginx -g 'daemon off;'"]
