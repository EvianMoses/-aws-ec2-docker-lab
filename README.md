# AWS EC2 & Docker Nginx Deployment Lab

## Lab Description
In this lab, I successfully launched an Ubuntu EC2 instance in AWS, installed Docker Engine, and deployed an Nginx web server container exposed to the internet on port 80. 
The provisioning process, Security Group configuration (allowing SSH and HTTP traffic), and the deployment itself went smoothly without any issues. Following the successful run and documentation, I terminated the EC2 instance to clean up the resources as requested.

## Proof of Execution (Screenshots)
Below are three screenshots from the execution process, confirming all lab objectives were met:

### 1. EC2 Instance Running in AWS
This screenshot displays the `nginx-docker-lab` instance in a running state within the AWS Management Console, showing its assigned public IPv4 address.
![EC2 Instance Running]
<img width="1668" height="814" alt="Screenshot 2026-05-26 202326" src="https://github.com/user-attachments/assets/c619c1a0-4fd4-40aa-a22d-8dbb1311edb3" />



### 2. Nginx Container Running in Docker
The output of the `docker ps` command from the server's terminal. This confirms the container is running and proves the ports are mapped correctly (`0.0.0.0:80->80/tcp`).
![Docker PS Output]
<img width="1723" height="823" alt="Screenshot 2026-05-26 202104" src="https://github.com/user-attachments/assets/a9e00eb3-6ebd-413b-8a57-79fcef72d5e3" />


### 3. Nginx Welcome Page Accessible
Verification of external web access – the browser accesses the instance's public IP address and successfully displays the "Welcome to nginx!" page.
![Nginx Welcome Page]

<img width="808" height="584" alt="Screenshot 2026-05-26 202029" src="https://github.com/user-attachments/assets/890383c5-e9a9-4573-b805-b9ed9a17049a" />


--------------------------------------------------------------------------------
