# docker_compose_web_dev
 docker compose web development environment with PHP Apache and MariaDB
 
   
 In the folder "docker_compose" is a docker-compose.yml that uses the already made Docker images
 for PHP Apache and MariaDB.
 
 Pre-Usage:
 Install Docker and Docker Compose.      
 Insert web content in "src" folder.  
 Insert your database dump with the name "my.sql" in the "docker_compose" folder.
 Open a console in the folder and type: "docker-compose -f docker-compose.yml up"   
 The images should now load and build.
 The webpage should be live @127.0.0.1:80    
 The database container can be reached @127.0.0.1:3306    
 (for editing purposes "Beekeeper Studio" or "DBeaver" can be used for example)
        
 Daily Usage:     
 Go to the docker_compose folder and type docker-compose up in your terminal. 
 
 please change the db settings to your needs!    


     
 I added an index.php to the source folder to check if the database connection works flawlessly   
 If you curl or browse to 127.0.0.1 it should return something like "Success: A proper connection to MySQL was made!" 

 ATTENTION: importing large databases can take some time!
 
 All the above was tested on Windows 10 with Docker Desktop.    
 @9R2by 2021
