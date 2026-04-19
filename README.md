# Highly Available Web Application on AWS
 Designed and deployed a production-style web architecture with HTTPS, load balancing, and custom domain routing.
 
## Overview
This project demonstrates deploying a secure, scalable web application using AWS services including EC2, Application Load Balancer, and ACM with a custom domain.

## Project Highlights
- Configured Application Load Balancer with HTTP → HTTPS redirection
- Secured application using AWS Certificate Manager (ACM)
- Connected custom domain via Namecheap DNS
- Implemented health checks and target group monitoring
- Achieved end-to-end HTTPS deployment

 ## Architecture Flow
Client → Domain (Namecheap DNS) → Application Load Balancer (HTTPS) → Target Group → EC2 Instance
 <img width="1536" height="1024" alt="serverless web application" src="https://github.com/user-attachments/assets/6e221c67-b11e-41e6-b5d4-75e954bef348" />

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
<img width="1908" height="945" alt="EC2 launched" src="https://github.com/user-attachments/assets/088c8723-1493-49f6-94f3-eee37e6553cb" />

### Load Balancer
<img width="1920" height="945" alt="Listener" src="https://github.com/user-attachments/assets/d0a39b96-37ae-4e7e-b7ce-2d985c749970" />

### Target Group Health
<img width="1912" height="956" alt="Healthy target" src="https://github.com/user-attachments/assets/8aa3b807-185f-4639-afc3-f14d192d15e7" />

### SSL Certificate (ACM)
<img width="1920" height="945" alt="ACM issued" src="https://github.com/user-attachments/assets/947a9a5b-d03f-41e6-aca6-a6835654dae2" />

### Live Website
<img width="1912" height="949" alt="website launched" src="https://github.com/user-attachments/assets/5b58f4b3-43b4-49d8-afbe-cffb17f811e8" />

## Deployment Steps
1. Launched EC2 instance (Amazon Linux 2023)
2. Installed and configured web server (Apache/Nginx)
3. Created Application Load Balancer and target group
4. Configured health checks for target group
5. Requested SSL certificate via AWS ACM
6. Validated domain using DNS (Namecheap)
7. Configured HTTPS listener (port 443)
8. Implemented HTTP → HTTPS redirection

## Challenges Faced
- DNS propagation delays during domain setup
- Troubleshooting NXDOMAIN errors
- Configuring correct CNAME records in Namecheap
- Ensuring ALB listener rules routed traffic correctly

## Key Learnings
- Load balancing concepts
- SSL/TLS setup using ACM
- DNS configuration
- Real-world deployment workflow

 This project was built through hands-on learning and AWS documentation.
