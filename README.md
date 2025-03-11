# Docker-Project
This repository contains the Docker Project document and its file

# Deploying a Web Application Using Docker and AWS Elastic Beanstalk  

## Project Overview  
This project demonstrates how to containerize a web application using **Docker** and deploy it to **AWS Elastic Beanstalk**. The goal is to showcase the use of containerization for scalable cloud deployment.  

## Technologies Used  
- **Docker** - For containerizing the application  
- **Nginx** - Web server for serving the application  
- **AWS Elastic Beanstalk** - For deploying and managing the application in the cloud  

## Key Steps  
1. Run an Nginx container locally  
2. Create a custom Docker image with an HTML file  
3. Build and run the custom Docker container  
4. Deploy the containerized application to AWS Elastic Beanstalk  
5. Clean up resources to avoid unnecessary charges  

## Project Files  
- `Dockerfile` - Defines the Docker image configuration  
- `index.html` - Sample HTML file served by the Nginx container  
- `README.md` - Project documentation  

## How to Run Locally  
1. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/Docker.git
   cd Docker
2. Build the Docker image:
docker build -t my-web-app .

3. Run the container:
   docker run -d -p 80:80 my-web-app

4. Open http://localhost in a browser to view the application

## Deployment on AWS Elastic Beanstalk
The application contains Dockerfile and index.html
It is deployed to AWS Elastic Beanstalk using the Elastic Beanstalk CLI

##Cleanup
To avoid unnecessary AWS charges, delete the Elastic Beanstalk environment and any associated S3 storage

## Author
Reesa Susan Sabu
