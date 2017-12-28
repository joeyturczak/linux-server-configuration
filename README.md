# linux-server-configuration

### Server information
* IP address: 52.33.93.225
* SSH port: 2200
* URL: http://52.33.93.225

### Summary of software installed
* Finger
* Apache2
* mod_wsgi
* pip
* Flask
* SQLAlchemy

### Summary of configurations made
* Added grader user and gave sudo permissions
* Changed default ssh port to 2200
* Only allow ssh connections
* Set up firewall to only listen on ports 2200, 80, and 123
* Upgraded and downloaded all software necessary for application
* Set up wsgi application to run web app

### Third-party resources used
* https://www.saltycrane.com/blog/2010/02/how-install-pip-ubuntu/
* http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
* https://www.jakowicz.com/flask-apache-wsgi/
* https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
