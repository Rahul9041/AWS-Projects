
#"Multi-Server Web Hosting with Custom Paths using EC2 and Apache"
(AWS EC2 + Apache HTTP Server + Linux Basics)

Short Description (LinkedIn Summary Style)
Successfully deployed three separate Linux-based EC2 instances on AWS, each hosting different static web content at specific URL paths. Configured Apache web server on each instance, created directory structures, and tested accessibility from a browser.

Key Highlights:

Server 1: Hosted Hello Welcome to Training at root / location.

Server 2: Hosted Hello Welcome to AWS at /aws location.

Server 3: Hosted Hello Welcome to Azure at /azure location.

Used AWS EC2, Security Groups, and Linux commands for configuration.

Skills Tag karna
On LinkedIn, Skills & Tools mein yeh add karo:

AWS EC2

Linux (CentOS / Ubuntu)

Apache HTTP Server

Networking & Security Groups

Static Website Hosting

Step-by-Step Approach (Post ke liye)
Tum apne LinkedIn post mein steps ke screenshots ke saath bata sakte ho:

Launched 3 EC2 Instances with Apache installed.

Edited /var/www/html/index.html for root page in Server 1.

Created /var/www/html/aws/index.html in Server 2 and configured.

Created /var/www/html/azure/index.html in Server 3 and configured.

Opened ports in Security Groups for HTTP traffic (Port 80).

Tested from browser:

http://<server1-ip>/ → "Hello Welcome to Training"

http://<server2-ip>/aws → "Hello Welcome to AWS"

http://<server3-ip>/azure → "Hello Welcome to Azure"
