# next.js image 
FROM node:14

# directory
WORKDIR /app

# copy .json files
COPY package*.json ./

# dependencies
RUN npm install

# copy all
COPY . .

# build app
RUN npm run build

# expose port
EXPOSE 3000

# Start app
CMD ["npm", "start"]
