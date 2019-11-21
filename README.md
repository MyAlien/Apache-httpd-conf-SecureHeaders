# Apache HTTPD Security Config
A config file for Apache HTTPD for securing and hardening prod deployments.

# Usage
## CentOS
1. Put this file into..
    * CentOS: /etc/httpd/conf.d/00_apache-security.conf
    * Debian: ?
    * Ubuntu: /etc/apache2/conf-available/00_apache-security.conf
        * Create a symlink in /etc/apache2/conf-enabled
1. Restart your webserver: 
    * apachectl restart
    * service httpd restart
    * service apache2 restart
    * /etc/init.d/httpd restart
    * /etc/init.d/apache2 restart
