#use an official Nginx image as the base image#
FROM nginx:alpine

#copy the static HTML file to Nginx HTML directory#
COPY index.html /usr/share/nginx/html/
#expose port 80#
EXPOSE  80

CMD ["nginx", "-g", "daemon off;"]
