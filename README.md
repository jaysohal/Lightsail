# Lightsail

Host a werdpress website on AWS Lightsail. 


## Create Instances
Created 2 Linux instances in Canada central zone that host Wordpress webiste. 

![alt text](https://github.com/jaysohal/Lightsail/blob/main/linstances.png)


## Create a Load Balancer
Created a load balancer that distributes the traffic evenly between the 2 instances mentioned above. 

![alt text](https://github.com/jaysohal/Lightsail/blob/main/lloadbalancer.png)

## Domain Name Configuration
Buy a domain name and change the name servers to have them point to AWS 53 systems. DNS resolves the load balancer domain name to custom domain "jaspreetsohal.com)

I bought a domain name "jaspreetsohal.com" through bluehost and updated the nameservers provided in lightsail DNS zone. 

## Create a SSL Certificate
Created a SSL certificate and attach it to load balancer. 

![alt text](https://github.com/jaysohal/Lightsail/blob/main/lloadbalancer1.png)

## Update DNS records
Add A records for DNS resolution
Add CNAME records for SSL certificate resolution

![alt text](https://github.com/jaysohal/Lightsail/blob/main/ldns.png)

## Check the website
Visit the website using custom domain name "jaspreetsohal.com" 

![alt text](https://github.com/jaysohal/Lightsail/blob/main/websitedns.png)
