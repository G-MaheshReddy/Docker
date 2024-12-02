#Get base image for Docker Container
FROM openjdk:17-jdk-slim

#Set the working dir in the image

WORKDIR app/

#copy the files from the host file system to the image file system

COPY . /app

#compile the program

RUN javac Hello.java

#command to run the java program

CMD ["java","Hello"]

