FROM node:18

# Set working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app
COPY . .

# Expose the backend port
EXPOSE 3089

# Start the server
CMD ["node", "server.js"]
