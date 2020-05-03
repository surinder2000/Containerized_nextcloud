First Docker Project under the mentorship of Mr. Vimal Daga (Linux World Informatics Pvt. Ltd.)
Integrating nextcloud and mysql using docker container 

Steps followed:

Install Docker in RHEL
Start docker services in the system using systemctl command
systemctl start docker

Get the image of nextcloud and mysql from docker hub using docker pull command
docker pull nextcloud
docker pull mysql:5.7

Install docker-compose in the system
Create nextcloud.yml file for integrating nextcloud and mysql in docker

Start container using docker-compose -f nextcloud.yml up -d 
