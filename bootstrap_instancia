Script para instalar o apache, inicia-lo e criar um arquivo html

#!/bin/bash
yum update -y
yum install httpd -y
service httpd start
chkconfig httpd on
cd /var/www/html
echo "<html><h1>Servidor OK</h1></html>" > index.html
