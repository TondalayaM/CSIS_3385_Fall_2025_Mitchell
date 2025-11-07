# Use a lightweight web server image
FROM nginx:alpine

# Copy HTML files to the server's public folder
COPY index.html /usr/share/nginx/html
COPY styles.css /usr/share/nginx/html

# Expose the web server port
EXPOSE 80
