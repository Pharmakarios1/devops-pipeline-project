# Use official Node image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY package*.json ./
RUN npm install

COPY . .

# Expose and start
EXPOSE 5173
CMD ["npm", "run", "dev"]
