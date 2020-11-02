#This specifies our base image is python:3
FROM python:3  
#This will copy the file to the container and if it doesn't exist it will create it.
COPY CA1.html / 
#This will run our image on port 8080
CMD python3 -m http.server 8080 
