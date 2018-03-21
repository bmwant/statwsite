# statwsite



### Development
Install with `npm install`

Serve locally with `http-server -p 8080


### Remote
Configure nginx
```
# ln -s `pwd`/site_nginx_config.conf.nginx /etc/nginx/sites-enabled/statwsite.conf
# nginx -t
# nginx -s reload
```
