# milobahgNifi

A Docker version of Apache Nifi

To run you will need to set the hostname flag and also update your /etc/hosts i.e: 127.0.0.1 localhost nifi

docker run -d -p 8080:8080 -h nifi milobahg/nifi:latest
