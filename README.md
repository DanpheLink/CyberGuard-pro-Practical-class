# CyberGuard-pro-Practical-class
Docker Composer file for practical classes

# Please Download the compose-yml file 

You can either download the ZIP file directly by accessing the code section where you can find the download ZIP section, 
OR
If you are using Linux system or have git installed in your windows system, you can directly access the file by: 

git clone https://github.com/DanpheLink/CyberGuard-pro-Practical-class.git

cd CyberGuard-pro-Practical-class

## After the you have successfully downloaded the file, run the following command

docker-compose -f compose.yml up -d --build

## check if the containers are up

DVWA and MariaDB by 
docker ps -a

# Now, open the DVWA and MariaDB in the browser by:
DVWA: Open http://localhost in your browser.
MariaDB: Connect to localhost:3306 using a MySQL client (with the credentials set in the docker-compose.yml file). 
