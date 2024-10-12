# Creating the DOCKER FILE for Running the VITE React app
FROM node:22-alpine

# moving to the working directory
WORKDIR /app

#copying the package json file 
COPY package.json .

#Installing the dependencies
RUN npm install

#Copy the running directory
COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev"]

