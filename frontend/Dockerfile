# Use an official Node.js runtime as the base image
FROM node:18

# Create and set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of your frontend code
COPY . .

# Expose the frontend port (e.g., 8080 or the port you're using)
EXPOSE 8080

# Start the frontend server
CMD ["npm", "run", "start"]
