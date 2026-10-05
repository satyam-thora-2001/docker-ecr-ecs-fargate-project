# Docker + Amazon ECR + ECS Fargate Project

This project demonstrates how to containerize a Python Flask application using Docker and deploy it on AWS ECS Fargate using Amazon ECR and an Application Load Balancer.

## Architecture

Internet
   |
   v
Application Load Balancer
   |
   v
Amazon ECS Fargate
   |
   v
Docker Container
   |
   v
Python Flask Application

Amazon ECR is used to store the Docker image.

## Technologies Used

- Python
- Flask
- Docker
- Amazon ECR
- Amazon ECS
- AWS Fargate
- Application Load Balancer
- Amazon CloudWatch
- Git & GitHub

## Project Structure

```text
Docker-ECR-ECS-Fargate-Project

 app.py
 Dockerfile
 requirements.txt
 README.md