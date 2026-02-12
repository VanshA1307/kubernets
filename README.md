# Node.js Docker DevOps App

## Run Locally
npm install
npm start

## Build Docker
docker build -t mynodeapp .

## Run Docker
docker run -d -p 3000:3000 mynodeapp
