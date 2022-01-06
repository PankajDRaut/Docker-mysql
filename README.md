# Docker-mysql
clone the above files in your pc and then follow the rest commands

Commands to be executed in terminal :
Sudo Docker build –t mysql  . 			 //this will build image using Dockerfile commands.

Sudo Docker images					  // To see the exisiting image

Sudo docker run -itd  --name abc –p 3306:3306 mysql   // To run the image

Sudo docker ps –a					// to check process is running 

Sudo docker exec –it abc bash 			// to execute the image  

Database commands:
Using above command we will enter in the image then following command will be used to enter in sql file.

Mysql –p  				//to enter in sql file
After this we have to enter the password and get logged in. then we select the database to be used.

Use pucsdStudents			//selecting the database

Select * from Students;			//to view the table.

