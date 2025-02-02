## Playbook to setup Nginx on Ubuntu and Debian
### Steps of the playbook: 
- apt update
- apt install nginx
- copy web-resourses
- copy a jinja template of nginx.conf
- copy logrotate
- start nginx 
- curl localhost
### + Role for adding module GeoIP to Nginx configuration
