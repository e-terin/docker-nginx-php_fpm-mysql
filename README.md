# docker-nginx-php_fpm-mysql

use for laravel

Install in PHPStorm

1. "git clone" repository in you projects folders
2. Rename file .env.example to .env
3. Custom networks section in .env if necessary and other params
4. Make a new project in PHPStorm (File-> New Project-> Select Path to folder -> Open )
5. Revert files in .idea folder
6. Reload PHPStorm
7. Run "UP" configuration
8. Go to http://172.85.0.10 web page and see "hello world". If you configured the network section in the .env file, follow http://<NETWORK_WEB_IP> URL
9. Put you project in folder "www"
