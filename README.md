# online food ordering system
Online Food Ordering System In Azure
#Azure Online Food Ordering System Project
This repository contains the setup and configuration for an online food ordering system deployed on Azure. The project involves the creation of two virtual machines (Server1 and Server2) running Ubuntu Server, the installation of the Apache2 server, and the setup of a MySQL database on both servers. Additionally, Azure Traffic Manager, Azure Monitoring Service, and DNS Zones are used to manage and monitor the deployment.

Sevices Used:
1)Traffic Manager:
In Microsoft Azure, a Traffic Manager is a service that allows you to distribute traffic across multiple endpoints (such as Azure regions, Azure App Service instances, or external, non-Azure endpoints) based on various routing methods. It is used to improve the availability and responsiveness of your applications by directing user traffic to the most suitable endpoint. 
2)Monitor Alert Rules: 
In Microsoft Azure, a Monitor Alert Rule is a configuration that you can set up to monitor various Azure resources for specific conditions or criteria, and then trigger an action (such as sending an email or running an Azure Function) when those conditions are met. Alert rules are part of Azure Monitor, which is a centralized monitoring and management service for Azure resources.
3)DNS Zones:
DNS Zones, in the context of Domain Name System (DNS), refer to distinct areas within the DNS namespace where DNS records are stored and managed. Each DNS zone contains a collection of DNS records that define the mapping between domain names and IP addresses, among other things. DNS Zones are organized hierarchically, and they are crucial for managing the domain name resolution process on the internet


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

![image](https://github.com/Ravan2602/Azure-project/assets/111184375/3b5d8569-b93d-47a9-a491-f491034ade3c)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/122d164d-ecd0-4d5e-a2f7-42cfcd2e9053)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/2442573e-4fbf-40e1-9957-60ef53e34bde)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/847a68f2-46d7-4716-a544-b589547c71a9)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/8ef3a371-599f-48a4-944a-514d3564ab0b)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/6b8690b2-38c2-45a5-b8bf-fa8ad2e204dd)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/ba9219ae-83ca-4124-9caf-9ed166c37475)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/cb5d72e3-3176-48df-bf76-5f31dff32045)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/d0753a98-1550-4bde-8d49-1835c937ad29)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/664dbec8-f1fd-4c04-b6d7-03695e00e422)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/edd5a1ce-cc50-4600-85b2-ea36a79b6bdd)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/ee89f33a-9c64-441e-88bd-9e6781e992a1)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/c325842f-6871-44b1-88ea-34944d5c3174)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/1e164bbb-be24-4b3e-a8d9-b6a54771aa8e)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/8144f8cf-5ab1-4ef2-a301-329222ee261c)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/9e196ff7-d472-4d1e-b4be-e4046beccbe9)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/d567ef49-0cad-42db-a3fb-be0707d62023)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/280d59b5-1d3a-47f0-9740-f5414aa9e0ea)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/9020f99a-8059-4b38-a312-cafd741335cc)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/8e22ca33-62c2-4c72-8401-322be9008e40)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/ae4579a0-7e8f-4284-8ef5-7866db21b02f)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/761e9d50-8070-4095-acab-76ac6657f757)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/0b67abe9-b4f4-46c6-b009-4104d1103d39)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/c2312b6b-0b12-491e-9416-d0b886b621d7)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/62abf156-5843-4bf1-ba06-c0c1f4f6b61f)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/bd50b906-22fb-43a0-a4ba-c6aed1d70cc1)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/cb86cba9-7fc2-41a0-bda6-04d71bbed6b1)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/f6aaf403-2980-451f-8497-f2c977e8ea58)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/f130e486-1dd8-424d-b590-e03323800d2c)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/3c601c83-7da4-4815-8e67-a9bb4442d2f0)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/a793af70-ceda-4686-ac37-f466d86a72b8)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/b5300482-a89b-44fa-b952-0d86be60be48)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/4cb02462-deba-4e84-90ee-334e3c0e795b)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/7a58732d-c7ff-47f3-95c5-037bee5e8682)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/c0339b9c-4567-45fa-a534-faaedc6c097b)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/4749ac02-c3e5-4e56-9813-2c659e0ad1d3)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/c4f9b19b-0995-4633-928c-ef6772dd0c1b)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/014b2353-bb18-476c-af4d-6346eddd76bc)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/a7f2abbd-dce6-468b-8993-575c5a9344c6)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/f42fbc2b-0ae9-4f4b-bb64-a45c6728f011)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/a7b62350-7522-4bed-b756-d38b8918d63c)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/75c4a5c7-f2ce-4e04-bab2-5ec496e31367)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/170ee2b9-75bc-4ee2-b1e4-73de89d3caa2)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/af97e073-ef5f-4523-a01b-84f6e860af64)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/bb91d577-9db2-49b9-a2de-c6d7920ff32e)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/a8f0a5b7-680b-460f-b670-31f7739f890d)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/61981b64-da35-49f3-97f1-aa5b8e6e6931)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/df411e60-069d-4890-8165-eb136ddc6d74)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/c9bbafe4-bb4b-4a69-b49c-cf86988ad3bf)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/db201590-c920-4f49-b8e8-f0c4624712b0)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/6ba02da7-f2cc-4ac6-96f3-11cc7087f755)

output overview :


![image](https://github.com/Ravan2602/Azure-project/assets/111184375/f9ec7493-1445-419c-bec6-8103492e059c)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/203adcae-3437-4dc3-a3a3-9c7e9b8c3485)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/8638456e-444f-4f11-bde5-ec178783efa8)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/2d8cd615-363b-4d3e-b722-bdaef88c6498)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/f858c4e7-50ae-435a-bbbc-823e6e28aa99)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/39f3570d-fd30-47ec-8505-a3655c715fb2)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/6ac03c6d-fe72-4fc8-aed7-ac2d1e94fe4e)
![image](https://github.com/Ravan2602/Azure-project/assets/111184375/6e558f91-d1c8-4409-9798-d88535762022)




