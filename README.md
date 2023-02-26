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
        
###### Start command for the Nginx server

    a) Start of the Nginx server
        sudo systemctl start nginx
        
    b) Status of the Nginx server
        sudo systemctl status nginx
        
    c) Stop of the Nginx server
        sudo systemctl stop nginx
        
    d) Restart of the Nginx server
        sudo systemctl reload nginx
     
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
          
      
###### Start 
    
    
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



# Advantage of Elastic compute cloud
1) Pay as you go

## Types of instances
1) On demand instances
2) Reserved instances
3) Spot instances

## On demand instance
When we have unpredictable workload-When I'm testing my application for the first time
-Pricing: price/sec or/min

## Reserved instances
When the work load is predicatble and stable- I will know how much load will our application take place
-Reserved capacity- 1yr/3yr

## Types of instances
1) Standard RI - No choice of reselling
2) Convertable RI - we can only upgrade
3) Schedule RI 

## Pricing of RI
1) Full upfront - Pay 100% once at a time.
2) Partial upfront - Pay 30%-50% once and remaining on monthly basis with reduced hourly basis
3) No upfront - Pay everything on monthly basis.


## Spot Instance
The instance that uses spare EC2 capacity that is available which is less than the on-demand price.
1) bid price >= aws spot price : will be given
2) bid < aws spot price: will not be given

Whenver the aws spot price is increased then the instance will be terminated.

## When we can go for spot instance
1) If we are not going to use on monthly basis
2) If we are not going to test the application then bid the price against the aws spot price.






