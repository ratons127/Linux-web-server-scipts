# Linux-web-server-scripts
Install Apache2 or nginx web server when installing Linux

## Scripts to install nginx server
```
#!/bin/bash

apt-get update
apt-get install nginx -y

echo "this is $(hostname)"> /var/www/html/index.html
```
Here "this is" a message and $(hostname) server IP


