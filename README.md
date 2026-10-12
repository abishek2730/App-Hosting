# AWS EC2 Static Website
Hosted a simple static website on an Amazon EC2 instance using Apache (httpd) on Amazon Linux.

## Steps
1. Launched a t3.micro EC2 instance (Amazon Linux 2023)
2. Allowed SSH (22) and HTTP (80) in the security group
3. Installed and started Apache: `sudo yum install httpd -y`
4. Added an index.html to /var/www/html
5. Opened the public IP in a browser

## Output
![Output](output.png)
