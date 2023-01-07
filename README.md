# Aws-Notes

# The Web Servers
## The Nginix server
  # The installation instruction of the server
  
   a) Update command
   
        sudo apt-get update
   
   b) Installing the package
   
        sudo apt-get install nginx
   
   c) Verfiying after installing the package
   
        sudo nginx -v
     
## The Tomcat server

  # The installation instruction of the server
## The Jenkins server
  # The installation instruction of the server
  
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

