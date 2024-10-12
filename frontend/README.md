# React App build build with Vite 

## Description,

## Local Environment setup
- install Node and npm 

## steps to run the frontend vite and react application
- move to the project directory
```bash
  cd frontend/
```
- install necessary node modules / project dependencies
```bash
  npm install
```
- run the project locally
```bash
  npm run dev
```
![image](https://github.com/user-attachments/assets/a385c57d-4674-4bd3-8a67-7251edb0ab62)

Hurrah 🥳 application is running successfully in the local host and can be accessed in http://localhost:5173

## Container Environment setup 
- install the Docker for building docker image and check its working fine.
```bash
  docker version 
``` 

## steps to containerize the Frontend

- docker command to build the container image
```bash
  docker build -t react-app .
```
- docker command to run the container image 
```bash
  docker run -itd --name=front-end -p 5173:5173 react-app 
```  
container image is up and running and access in localhost and in machine's associated public ip 
