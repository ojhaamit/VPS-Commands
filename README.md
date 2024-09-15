# Commands for working on Digital Ocean's VPS for hosting websites
	* apache2ctl configtest               #To test apache configs
	* service apache2 restart             #To restart the apache service
	* a2dissite 000-default.conf          #To disable any config
	* a2ensite amit-ojha.conf             #To activate any config
	* cd /etc/apache2/sites-available/    #To list all available configs
	* cd /var/www                         #All websites should be present here
	* ufw app status                      #To check firewall status
	* ufw allow in "Apache Full"          #To allow any app to pass through firewall
	* ufw app list                        #To get list of apps
	* ufw enable                          #To enable firewall
	* sudo apt install apache2            #To install apache server
