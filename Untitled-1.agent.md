version:3
services:
apache
build:/apache
ports:
-80:80
volumens:
-,/src/var/www/html
