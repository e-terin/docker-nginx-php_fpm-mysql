# docker-nginx-php_fpm-mysql

use for laravel

Install in PHPStorm

1. Create project from VCS in PHPStorm IDE:
   1. Open any you existing project
   2. File-> Close Projects or Close All Projects -> Get from VCS
   3. Pick this repository https://github.com/e-terin/docker-nginx-php_fpm-mysql, then "OK"
2. Rename file .env.example to .env
3. Custom networks section in .env if necessary and other params
4. Make a new project in PHPStorm (File-> New Project-> Select Path to folder -> Open )
5. Revert files in .idea folder
6. Reload PHPStorm
7. Run "UP" configuration
8. Go to http://172.85.0.10 web page and see "hello world". If you configured the network section in the .env file, follow http://<NETWORK_WEB_IP> URL
9. Put you project in folder "www"
