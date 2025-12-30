FROM node:18-alpine

# Setting working dir inside container
WORKDIR /app

# Copy all package files
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

