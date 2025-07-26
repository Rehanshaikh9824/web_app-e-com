================ overview ======================

This project demonstrates how to deploy a high-availability, scalable eCommerce web application on AWS using Docker, Terraform, and NGINX. The app is built with a React frontend and Node.js backend, and uses MySQL for managing product, user, and order data.

===============Tool used ====================

•	Cloud -----  AWS (EC2, VPC, Subnets, RDS, S3, Route 53, IAM)
•	IaC ----- Terraform
•	Containerization ----- Docker
•	Reverse Proxy ----- NGINX
•	Frontend ----- React
•	Backend ----- Node.js
•	Database ----- MySQL
•	Version Control ----- Git, GitHub

============== Infrastructure Setup ================

  - Provisioned using -- Terraform 
Create -
  - VPC, Public Subnets, Internet Gateway
  - EC2 Instances, Security Groups
  - IAM Roles, RDS Instance

================= App Deployment =====================

•	Dockerized React frontend and Node.js backend
•	NGINX routes traffic to backend APIs
•	MySQL stores eCommerce data (users, products, orders)

================= Achievements =========================

•	Reduced environment issues by 30% using Docker
•	Automated deployment with Terraform
•	Scalable architecture with public subnet access control

================= What I Learned =======================
•	Real-world IaC on AWS
•	End-to-end deployment using DevOps tools
•	GitHub for version controlled infrastructure
-------------------------------------------------------------------------------------------------------------------------------
