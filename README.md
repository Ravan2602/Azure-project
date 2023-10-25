# AzureProject
Online Food Ordering System In Azure
#Azure Online Food Ordering System Project
This repository contains the setup and configuration for an online food ordering system deployed on Azure. The project involves the creation of two virtual machines (Server1 and Server2) running Ubuntu Server, the installation of the Apache2 server, and the setup of a MySQL database on both servers. Additionally, Azure Traffic Manager, Azure Monitoring Service, and DNS Zones are used to manage and monitor the deployment.

##Project Components
Virtual Machines

#Server1:
Apache2 server installed.
PHP files uploaded to the HTML directory.
MySQL database for the online food ordering system.

#Server2:
Apache2 server installed.
PHP files uploaded to the HTML directory.
MySQL database for the online food ordering system.

##Azure Services:
1)Azure Traffic Manager:
Configured to manage traffic between Server1 and Server2.
Ensures high availability and load balancing for the online food ordering system.

2)Azure Monitoring Service:
Alert rule set up to send notifications (email and SMS) when the system's resource usage exceeds 80% threshold.

3)DNS Zones:
Used for mapping the deployment to a custom domain.
www.kyutorn.site is configured to point to the online food ordering system.

##Deployment Instructions
1)Deploy two virtual machines running Ubuntu Server.
2)Install Apache2 and MySQL on both Server1 and Server2.
3)Upload the PHP files to the HTML directory on both servers.
4)Configure the MySQL databases for the online food ordering system on both servers.
5)Set up Azure Traffic Manager to distribute traffic between Server1 and Server2.
6)Configure the Azure Monitoring Service alert rule for resource monitoring.
7)Create DNS Zones for the custom domain (e.g., www.kyutorn.site) and activate it.
8)Access the online food ordering system by visiting www.kyutorn.site in a web browser.
9)Monitoring and Alerts
10)The system is set to send email and SMS notifications when the resource usage exceeds 80%.
