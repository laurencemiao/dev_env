sudo ln -s /home/larry/Workshop/dev_env/etc/php-fpm.conf /etc/php-fpm.d/larry.conf
sudo ln -s /home/larry/Workshop/dev_env/etc/nginx.conf /etc/nginx/conf.d/larry.conf

sudo systemctl status php-fpm.service
sudo systemctl status nginx.service
