# intuji-devops-internship-challenge
# Q.1
# step-1 : Creating a vagrant file to automatically create VM in VirtualBox and downloading docker 
# step-2 : Using the command vagrant up so start the VM and install docker
# step-3 : SSH to the vm and checking if docker is installed or not
# Q.2
# step-1 : cloning the given git reposetry
# Q.2.1
# step-1 : Creating a Dockerfile which will install git and apache2 
# step-2 : Also, It will clone the github repositry and save the file in /var/www/html directior
# step-3 : Exposing the Docker Image in port 80
# step-4 : navigate to the directory wher Docker file is present
# step-5 : using docker run command with port mapping 8080 to 80 and naming the image my-web-app
# step-6 : accessing the website with the ipaddress:port: 192.168.1.64:8080
# Q. 2.2
# step-1 : Creating a repositry named apache2
# step-2 : Using the command Docker tag my-web-app akaxyz/apachey2 where my-web-app is the name of the docker image and akaxyz/apache2 is repositry name  
# step-3 : Using docker login command; login to docker hub 
# step-4 : Using the command docker push akaxyz/apache2:latest to push the docker image in the repositry or docker hub
# Q. 3
# step-1 : Creating a docker compose file
# step-2 : Using nginx:latest as the docker image 
# step-3 : Port mapping 8080 to 80
# step-4 : setting up volume and seting private netwokr to bridge
# step-5 : using the command docker-compose up 
# step-6 : Checking if Nginx is hosted in localhost:8080
# Q.4
# step-1 : creating a vagrant file to install ubuntu in virtualbox and downloading jenkins
# step-2 : Using Vagrant up and ssh to the VM
# step-3 : Downloading docker Engine
# step-4 : Adding jenkins to docker group
# step-5 : Seting up jenkins
# step-6 : Creating a freestyle Project
# step-7 : Installing Plugins like Docker Pipeline and Git
# step-8 : Seting up git url for source code
# step-9 : Seting up git url for dockerfile
# step-10 : Writing bash script to build image with name jenkins
# step-11 : Using docker run and portmapping 80 to 80 and image name
# step-12 : Checking if Job has succeeded
# step-13 : checking if Contents of dockerfile is hoster 

# Note: Necessary screenshots are provided in ss directory