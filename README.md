# aws-web-app-alb-https
Deployed a highly available and secure web application on AWS using EC2, Application Load Balancer, ACM (HTTPS), and custom domain integration.
# Highly Available Web Application on AWS

## Overview
This project demonstrates deploying a secure, scalable web application using AWS services including EC2, Application Load Balancer, and ACM with a custom domain.

## Project Highlights
- Configured Application Load Balancer with HTTP → HTTPS redirection
- Secured application using AWS Certificate Manager (ACM)
- Connected custom domain via Namecheap DNS
- Implemented health checks and target group monitoring
- Achieved end-to-end HTTPS deployment
  
## Architecture
- EC2 Instance (Amazon Linux 2023)
- Application Load Balancer (ALB)
- Target Group
- AWS Certificate Manager (ACM)
- Custom Domain (Namecheap DNS)

## Features
- HTTPS enabled using ACM
- Load balancing using ALB
- Domain integration
- Health checks and target monitoring

## Live URL
https://www.mehrwancloud.org

## Screenshots
(Add images here)

## Steps
1. Launch EC2 instance
2. Install web server
3. Configure ALB and target group
4. Request SSL certificate using ACM
5. Configure DNS records in Namecheap
6. Enable HTTPS listener

## Key Learnings
- Load balancing concepts
- SSL/TLS setup using ACM
- DNS configuration
- Real-world deployment workflow

- Built through hands-on learning and AWS documentation.
