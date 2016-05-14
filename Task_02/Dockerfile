####################################################################
# Dockerfile to Run Simple PHP Script Which Outputs 'Hello,Docker'
# Based on Ubuntu
####################################################################

# Set the base image to Ubuntu
FROM ubuntu:14.04

# File Author / Maintainer
MAINTAINER Edwin Fernandez <efernand.cs@gmail.com>

# Update the repository sources list && 
# Install PHP 
RUN apt-get update && apt-get install -y \
	php5
	
#Copy "Hello Docker" PHP CLI Application to the container
COPY hello_docker /home/ed/


#Execute PHP CLI Application
CMD /home/ed/hello_docker


