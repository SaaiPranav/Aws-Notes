# Aws-Notes

# The Web Servers
## The Nginix server
###### The installation instruction of the server
  
   a) Update command
   
        sudo apt-get update
   
   b) Installing the package
   
        sudo apt-get install nginx
   
   c) Verfiying after installing the package
   
        sudo nginx -v
     
## The Tomcat server

  The installation instruction of the server
## The Jenkins server
######  The installation instruction of the server
  
    a) The key command
    
          curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
          /usr/share/keyrings/jenkins-keyring.asc > /dev/null
    
    b) The Apt repository command
    
          echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
          https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
          /etc/apt/sources.list.d/jenkins.list > /dev/null
    
    c) Update the packages and installation command
    
          sudo apt-get update
          sudo apt-get install fontconfig openjdk-11-jre
          sudo apt-get install jenkins
    
    
## The Apache server
## The IIS server
## The lighttpd server
## The Jigsaw server

### The Cloud provider
1) AWS
2) Azure
3) GCP
4) Alibaba cloud
5) IBM cloud

Category of 
a) Public cloud provider
b) Private cloud provider
c) Hybrid cloud provider

Types of services
1) SAAS(Software as a service):google cloud
2) PAAS(Platform as a service):AWS
3) IAAS:AWS

latency: The time taken for the application to display
edge of location server/point pf present
cdn(content delivery network)



