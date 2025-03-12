

## Stack Setup Instructions

````
# Setup directory structure and files
mkdir -p app/static nginx

# Create the following files:
# app/app.py          # Flask application code
# app/requirements.txt # Python dependencies
# app/Dockerfile      # Flask application Dockerfile
# nginx/default.conf  # Nginx proxy configuration
# docker-compose.yml  # Defines all services

# Start the application stack
docker-compose up -d

# Check running containers
docker-compose ps

# Test the API
curl http://localhost/

# View logs
docker-compose logs flask
````
