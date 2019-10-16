FROM nginx:1.9.1
EXPOSE 80
CMD ["/bin/bash","-c","date > /usr/share/nginx/html/index.html && exec nginx -g 'daemon off;'"]
