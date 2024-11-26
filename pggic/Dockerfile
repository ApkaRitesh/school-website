# Use the official Nginx image
FROM nginx:latest

# Copy the HTML files to Nginx's default directory
COPY home.html /usr/share/nginx/html/
COPY aboutus.html /usr/share/nginx/html/
COPY map.html /usr/share/nginx/html/
COPY contact.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/
COPY script.js /usr/share/nginx/html/
COPY image/ /usr/share/nginx/html/image/  
# Corrected to copy the 'image' folder

# Optional: Copy a custom nginx.conf if you need any special configuration
# COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 to access the website
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]