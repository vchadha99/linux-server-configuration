# udacity-linux-server-configuration-project
Final project for the Udacity Full Stack Web Developer's Nanodegree 

## Intro

- Linux distribution Ubuntu 16.04 LTS
- Amazon Lightsail Virtual Private Server
- Loaded my 'Catalog' project from earlier in the year
- Used PostGres database instead of SQL
  
## Configurations

- Updated packages to most recent versions
- Changed ssh port from 22 to 2200
- Enabled ports: 80, 123, 2200
- Set firewall rules using UFW

## Login Instructions for user 'grader'
 
- SSH port: 2200  
- URL: http://13.234.226.183 
- Password: sudo
- phrase sudo123
- Login using this command: `ssh -i id_rsa -p 2200 grader@13.234.226.183`

## Software Installed

- apache2
- postgresql
- git
- python3-pip
- httplib2
- requests
- oauth2client
- sqlalchemy
- flask
- libpq-dev
- psycopg2

## Resources

- [How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)  
- [Udacity Knowledge Forums](https://knowledge.udacity.com/)
- [boisalai/udacity-linux-server-configuration](https://github.com/boisalai/udacity-linux-server-configuration)
