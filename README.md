Integrating nextcloud and mysql using docker container 

Steps followed:

Install Docker in RHEL 8

Start docker services in the system using systemctl command

            systemctl start docker

Get the image of nextcloud and mysql from docker hub using docker pull command

            docker pull nextcloud

            docker pull mysql:5.7

Install docker-compose in the system

Create file_name.yml file for integrating nextcloud and mysql in docker

Start container using 
      
           docker-compose -f file_name.yml up -d 
