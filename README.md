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
### EC2 Instance
![EC2](screenshots/ec2.png)
<img width="1908" height="945" alt="EC2 launched" src="https://github.com/user-attachments/assets/088c8723-1493-49f6-94f3-eee37e6553cb" />
### Load Balancer
![ALB](screenshots/alb.png)
<img width="1920" height="945" alt="Listener" src="https://github.com/user-attachments/assets/d0a39b96-37ae-4e7e-b7ce-2d985c749970" />
### Target Group Health
![Target Group](screenshots/target-group.png)
<img width="1912" height="956" alt="Healthy target" src="https://github.com/user-attachments/assets/8aa3b807-185f-4639-afc3-f14d192d15e7" />
### SSL Certificate (ACM)
![ACM](screenshots/acm.png)
<img width="1920" height="945" alt="ACM issued" src="https://github.com/user-attachments/assets/947a9a5b-d03f-41e6-aca6-a6835654dae2" />
### Live Website
![Website](screenshots/website.png)
<img width="1912" height="949" alt="website launched" src="https://github.com/user-attachments/assets/5b58f4b3-43b4-49d8-afbe-cffb17f811e8" />

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

  ## Built through hands-on learning and AWS documentation.
