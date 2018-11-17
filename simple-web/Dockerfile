# Add base file
FROM node:alpine

# Set working directory
WORKDIR /usr/app

# Copy package.json and run npm install
COPY ./package.json ./
RUN npm install

# Copy rest of the contents
COPY ./ ./

# Run command
CMD ["npm", "start"]