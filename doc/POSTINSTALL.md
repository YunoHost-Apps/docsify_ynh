The files served are located in `__DATA_DIR__/mysite`

Use init to generate your docs. You may open a 'Docsify shell' with `sudo yunohost app shell __APP__`, and then `./bin/docsify init __DATA_DIR__/myothersite` 

You will have to change NGINX server path accordingly: `/etc/nginx/conf.d/__DOMAIN__/...`
