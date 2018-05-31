# nginx-config
nginx serving from user folder ~/Sites

This repo outlines Hugh's Nginx set up. He is running Ubuntu 16.04 and does not want web-pages hosted on his machine browsable by the local area network, but does want to have local copies of several self hosted websites. He also does not want to host the files in the default location. Rather he would like to host them at `~/Sites/Nginx/someSpecific-Site`

His preference would be to either have `localhost:111111111 <--some port number`or `localhost/somefolder`.

## Nginx is located at

```
$pwd /etc/nginx
$ls 

conf.d
fastcgi.conf
fastcgi_params
koi-utf
koi-win
mime.types
nginx.conf
proxy_params
scgi_params
sites-available
sites-enabled
snippets
uwsgi_params
win-utf

```
## Default hosting location

```
$PWD /var/www/html
$ls
index.apache2-2.html
index.apache2.html
index.nginx-debian.html
index.php
```
