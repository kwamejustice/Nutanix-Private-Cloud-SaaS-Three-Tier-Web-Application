# Nutanix-Private-Cloud-SaaS-Three-Tier-Web-Application

Private Cloud SaaS Web Application
This project includes the following details
- A blueprint to deploy and configure a three-tier web application with a load balancer, web server and database VM hosted on the Nutanix Private Cloud
- The web tier has scaling capabilities to scale in ans scale out changing population by a count of one (1)
- A database end user with the ability to make a backup

      ## The teccadm superuser with the ability to create the web server VMs and Load balancer
         The teccdba superuser with all the root credentials on the MySQl server
         Included in this repo are the ssh credentials for both root user 

- CentOS Linux 8 was the underlying operating system used to configure the VMs
- The load balancer VM is a monolith and uses the latest HAProxy software included with the OS
- The web tier uses Apache web server and the latest version of httpd software included with the OS.
  
      ## The deployment scenario named small with each VM using the same resource sizes: 
         1 vCPU
         1 core
         1GB RAM
         
 
# No VM resource parameters can be changed by the end user, except the Database VM memory
