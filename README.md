# Commands for working on DigitalOcean's VPS for hosting websites
	* apache2ctl configtest               # To test apache configs
	* service apache2 restart             # To restart the apache service
	* a2dissite 000-default.conf          # To disable any config
	* a2ensite amit-ojha.conf             # To activate any config
	* cd /etc/apache2/sites-available/    # Directory where per sites virtual hosts can be stored
	* cd /var/www                         # Directory where web-contents should be present
	* ufw app status                      # To check firewall status
	* ufw allow in "Apache Full"          # To allow any app to pass through firewall
	* ufw app list                        # To get list of apps
	* ufw enable                          # To enable firewall
	* sudo apt install apache2            # To install apache server
 	* cd /var/log/apache2		      # Directory to get the access and error logs
