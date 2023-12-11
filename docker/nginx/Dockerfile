# Use Bitnami's Nginx 1.24 image
FROM bitnami/nginx:1.24

# Expose port 80 for HTTP communication
EXPOSE 80

# (Optional) Copy your Nginx configuration file
# Assume you have a custom Nginx configuration file, such as 'my_nginx.conf'
# COPY dev.aitkenjoinery.conf /opt/bitnami/nginx/conf/nginx.conf

# (Optional) If you want to host a static website or PHP application, you can copy files into the image
COPY ../../ /app

# Set the working directory
WORKDIR /app

# (Optional) Set environment variables, adjust as needed
# ENV NGINX_HTTP_PORT_NUMBER=80
# ENV NGINX_HTTPS_PORT_NUMBER=443

# Set user (if you need to run as a non-root user)
# USER 1001
