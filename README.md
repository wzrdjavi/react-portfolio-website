# react-portfolio-website

## Link
Deploment link: 

## Description 
Portfolio site to showcase the projects that I have completed.

## Usage 
- This website is my portfolio
- Showing my experience 
- Users can see my work on my portfolio.
- Displaying my skills on my Resume.



 {
    "name": "",
    "version": "1.0.0",
    "description": "",
    "main": "index.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "if-env NODE_ENV=production && npm run start:prod || npm run start:dev",
        "start:prod": "cd server && npm start",
        "start:dev": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"",
        "install": "cd server && npm i && cd ../client && npm i",
        "seed": "cd server && npm run seed"
    },
    "repository": {
        "type": "git",
        "url": ""
    },
    "author": "",
    "license": "ISC",
    "bugs": {
        "url": ""
    },
    "homepage": "",
    "dependencies": {
        "apollo": "^2.34.0",
        "babel-template": "^6.26.0",
        "concurrently": "^7.6.0",
        "express": "^4.18.2",
        "mongo": "^0.1.0",
        "mongoose": "^6.7.4",
        "nodemon": "^2.0.20",
        "react": "^18.2.0",
        "react-modules": "^1.0.8",
        "stripe": "^11.1.0"
    }
}
