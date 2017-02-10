## nginx
/Applications/MAMP/conf/nginx/nginx.conf

Sous http
include /Users/mgervais/pwen/private/mamp/nginx.conf;




## mysql
Copie /Applications/MAMP/Library/support-files/my-small.cnf vers mysql.conf

ln -s /Users/mgervais/pwen/private/mamp/mysql.conf /Applications/MAMP/conf/my.cnf



## php
Copie /Applications/MAMP/bin/php/phpX.X.X/conf/php.ini vers phpX.X.X.ini

ln -s /Users/mgervais/pwen/private/mamp/phpX.X.X.ini /Applications/MAMP/bin/php/phpX.X.X/conf/php.ini
