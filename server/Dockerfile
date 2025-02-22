# Use official Node.js image
FROM node:16-alpine

# Set working directory inside the container
WORKDIR /app

# Copy package.json first (to install dependencies before copying all files)
COPY package.json ./

# Install dependencies
RUN npm install

# Copy all source code (including server.js)
COPY . .

# Expose port 5000
EXPOSE 5000

# Start the server
CMD ["node", "server/server.js"]
