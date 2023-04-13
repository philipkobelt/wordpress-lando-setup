# wordpress-lando-setup

## Initialise the whole setup
lando init --source remote --remote-url https://wordpress.org/latest.tar.gz --recipe wordpress --webroot wordpress --name wordpress-lando-setup

# Should start up successfully
lando start

## Visit the local site
open https://lando-wordpress.lndo.site

## Destroy the site
lando destroy -y