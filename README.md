# docker_compose_web_dev
 docker compose web development environment with PHP Apache and MariaDB
 
   
 In the folder "docker_compose" is a docker-compose.yml that uses the already made Docker images
 for PHP Apache and MariaDB.
 
 Pre-Usage:
 Install Docker and Docker Compose.   
 
 Usage:    
 Insert web content in "src" folder.  
 insert your database dump with the name "my.sql" in the "docker_compose" folder.
 open a console window in the folder and type: "docker-compose -f docker-compose.yml up"   
 The images should now load and build.
 The webpage should be live on: 127.0.0.1:80    
 The database container can be reached @127.0.0.1:3306    
 (for editing purposes "Beekeeper Studio" can be used for example)   
 
 please change the db settings to your needs!    


