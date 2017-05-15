# logstash
this is a logstash docker project

start:
docker run --name logstash -dit -p 9600:9600 -v data:/usr/local/logstash/data mypjb/logstash
 
