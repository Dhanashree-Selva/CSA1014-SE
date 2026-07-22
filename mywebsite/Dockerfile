# Use the official lightweight Nginx web server image
FROM nginx:alpine

# Copy your HTML and CSS files into Nginx's default public directory
COPY index.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/

# Expose port 80 to allow traffic into the container
EXPOSE 80