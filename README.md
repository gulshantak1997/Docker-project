# Docker-project


I have created a project for installation of ghost. 
Ghost is a free and open source blogging platform written in JavaScript and distributed under the MIT License, designed to simplify the process of online publishing for individual bloggers as well as online publications.

# Requirements:-

- Redhat Enterprise Linux
- Docker

# Disable the following:-

- Disable firewalld using systemctl stop firewalld command.
- Disable SELinux using setenforce 0 command.

# Start docker services using following command:-

   systemctl start docker
 
# Requirement of images:-

- mysql:5.7
- ghost:latest

# Docker compose:-

First install docker compose.
You can edit or create its file using vim docker-compose.yml command.

# Docker-compose-up:-

As in the screenshot (docker-compose up) is used to complete the setup.

# Ghost:latest

You can now browse and type localhost:81 , using this you will be able to see your ghost.

# Docker compose start/stop:-

After using docker-compose up now in one click you can stop or start the whole setup.

- To stop:-
        docker-compose stop

- To start again:-
        docker-compose start
        
# Docker-compose down

 Now you can easily stop the containers using docker-compose down command.
 

  
