# Base Image
FROM ubuntu:16.04 

# Owner Image
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update APT Repo
RUN apt-get update

# Install Apache Package
RUN apt-get install apache2 -y 


# Run Apache Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
