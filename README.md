# TW_Test
TW Test

UAT Environment:

Setup:

Docker Setup - AWS EC2 Machine
Docker version 18.03.1-ce
docker-compose version 1.21.2

Application Environment-
- Nginx to run static content ( Alternative could be Apache)
- Jetty to run Dynamic content (Atrributes - Througput and Performance)

Images-
Static- shefalidocker/companynews_static
Dynamic- shefalidocker/companynews_dynamic


Production Plan:



AWS Cloud with- ECS Cluster, Application Load Balancer, Cloud Watch, Cloud Front, VPC-
Benefits:
- High Flexibility and Availablity.
- Scalabilty and Redundancy with provision to create alarms with Cloud Watch to scale services up and down.
- Use ALB to route requests with SSL termination.
- Use HTTPS with certificate on Load Balancer .
- Static files could be hosted on Cloud Front for higher availability
- Use VPC with NACLs and security groups for security.



