# dockerprep
a simple guide for local dockerprep (win/linux/macos)  
  
1. docker build -t hello-world .  
2. docker run -p 80:80 hello-world  
3. docker run -p 80:80 -v /path/to/projectfolder/src/:/var/www/html/ hello-world  
  
helpful commands  
1. docker info  
2. docker ps
