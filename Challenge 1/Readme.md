This template will deploy:

One Virtual Network with four subnets
4 Network Security Group, one for each subnet
External Load Balancer to load balance Web Traffic(HTTP & HTTPS) to web servers
Internal Load Balancer to load balance traffic for app VM's
2 Public IP’s, one for external Load balancer and other for Jump VM
Virtual Machine Availability sets for Web Tier, Application Tier and Database tier
One Jump VM to faclitate RDP access to all other tier VMs
Multiple windows VMs
