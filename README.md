# CyberGuard-pro-Practical-class
Docker Composer file for practical classes

# Please Download the compose-yml file and run the following command

docker-compose -f compose.yml up -d --build
check if the containers are up
DVWA and MariaDB by 
docker ps -a

# Now, open the DVWA and MariaDB in the browser by:
DVWA: Open http://localhost in your browser.
MariaDB: Connect to localhost:3306 using a MySQL client (with the credentials set in the docker-compose.yml file). 
