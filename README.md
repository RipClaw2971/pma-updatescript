# phpMyAdmin updatescript for your shell
With this script it will be easy to update to phpMyAdmin's latest version. Directly from your shell.

## Installation
Copy the script to any location of your machine.   
IMPORTANT: Open it and correct the settings.

If you set f.e. LOCATION="/var/www" your PMA installation will be installed into /var/www/pma  


## Usage
For installing the latest version start the script like this (in a cronjob if you want)

    bash pma-update.sh
	
If you want to install a specified version

    bash pma-update.sh 3.5.0


 
