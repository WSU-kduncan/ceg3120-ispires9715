Part 2:

1. Files are configured by adding the web server & loadbalancer IP addresses.

2. To SSH between the two instances with their private IP addresses you'll need to make a rule on both instances that allows ssh traffic from the other ip address.

3. To install: 'sudo apt-get install haproxy'

   Files that it changed and their location when the program was installed: etc/haproxy/haproxy.cfg
   
   Configs set: Just the default configuration was set up.
   
   How to reboot after config update: 'sudo systemctl restart haproxy'
   
   Resource I used: https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts
                    https://dilliganesh.wordpress.com/2017/03/02/how-to-configure-http-load-balancer-with-haproxy-on-linux/
                    
               -These sources explained haproxy and load balancing as well as gave an example of /etc/hosts files for the webservers
   
   
   
   
4. How to install: 'sudo apt-get install apache2'

   Files that it changed and their location when the program was installed: '/etc/apache2/sites-enabled/000-default.conf'
   
   Configs set: Only the default was set up.
   
   I restarted apache2 by typing in this command: 'sudo service apache2 reload'
   
   Resource that I used: https://ubuntu.com/tutorials/install-and-configure-apache#5-activating-virtualhost-file
        -It described some of the basics for the apache program.
