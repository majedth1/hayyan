FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

# Development mode - no build step needed
CMD ["npm", "run", "dev"]