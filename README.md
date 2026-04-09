
<img width="1920" height="1080" alt="{9EC8A253-6175-45AB-8D32-793A1CBDCE38}" src="https://github.com/user-attachments/assets/b44b1df5-ff6f-4c7b-9a9c-d45c14c9131d" />





![d72e4d0d-d8a2-43f4-96c3-4db5a21b3f95](https://github.com/user-attachments/assets/8996d107-15f9-4772-99f7-c71c42b2f5af)






# aws-wordpress-3tier-project
This project demonstrated how I design and deploy a 3-Tier WordPress Website on AWS, emphasizing scalability, security, and high availability
# AWS WordPress 3-Tier Project

## Overview
This project demonstrates deploying a WordPress application on AWS using a 3-tier architecture.

## Architecture
- EC2 (Web Server)
- Apache (Web Server)
- PHP-FPM
- WordPress
- VPC with Public and Private Subnets
- Security Groups
- NAT Gateway

## What I Built
- Configured EC2 instance
- Installed Apache and PHP
- Deployed WordPress
- Connected WordPress to database
- Configured networking (VPC, subnets, security groups)

## Issues I Solved
- Apache showing directory instead of WordPress
- PHP not running (fixed by installing php-fpm)
- Connected Apache to PHP-FPM

## Screenshots
See the /screenshots folder

## How to Access
[http://YOUR-PUBLIC-IP](http://44.200.220.47/wp-admin/)

## Author
Yonathan Jaramillo
