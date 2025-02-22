# Use an official Node.js runtime
FROM node:16-alpine

# Set working directory
WORKDIR /app

# Copy project files
COPY . .

# Expose port 3000
EXPOSE 3000

# Start a simple static server
CMD ["npx", "http-server", "-p", "3000"]
