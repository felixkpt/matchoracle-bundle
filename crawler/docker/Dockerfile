# crawler/Dockerfile
FROM node:20

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY . .

# Install dependencies
RUN npm install

# Expose port
EXPOSE 3065

CMD ["node", "index.js"]
