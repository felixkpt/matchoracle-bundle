# frontend/Dockerfile
FROM node:20

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY . .

# Install dependencies
RUN npm install

# Build application
RUN npm run build

# Expose port
EXPOSE 3075

CMD ["npm", "start"]
