# FROM node:20

# WORKDIR /usr/src/app

# COPY . .

# RUN npm install

# EXPOSE 3000

# CMD ["node", "index.js"]

FROM node:20

WORKDIR /usr/src/app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of your project files
COPY . .

EXPOSE 3000

CMD ["node", "index.js"]

