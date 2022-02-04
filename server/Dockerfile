FROM node:16.13.0

# Step 4.1 - Add container working directory
WORKDIR /server

# Step 4.2 - Copy npm dependencies
COPY package.json /server/package.json

# Step 4.3 - Install dependencies
RUN npm install

# Copy app source code

COPY . .

#Expose port and start application

EXPOSE 8080

CMD ["npm", "start"]