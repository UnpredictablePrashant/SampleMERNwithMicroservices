# Use an official Node.js image from Docker Hub
FROM node:14

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code to the container
COPY . .

# Expose the port on which your React app runs (typically 3000)
EXPOSE 3000

# Command to run the application
CMD ["npm", "start"]
