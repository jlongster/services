
* git clone https://github.com/jlongster/services.git /etc/sv
* create local configs for desired services
** example (redis): cd redis/conf; cp redis.conf redis-local.conf;
* symlink desired services 
** example (redis): ln -s /etc/sv/redis /service