# Pull nginx base image
FROM nginx:1-bullseye

# Expost port 80
EXPOSE 80

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf

# Start up nginx server
CMD ["nginx"]

