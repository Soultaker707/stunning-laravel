

Read Me file - All commands used during different checkpoints


Checkpoint1: 1- No command here. 2- sudo: sudo stands for "superuser do" and is used to execute commands with elevated privileges . It allows them to use commands that only have access by the root user.

apt-get: It is used to install, upgrade, and remove software packages, as well as manage dependencies between packages. The apt-get command downloads packages from software repositories and installs them on your machine. 3- No command 4- sudo agpt-get install apache2 mysql-server php-mysql php libapach2-mod-php php-pear curl php-curl php-cli git (during the recording i used sudo apt-get every line, after i finished i rememberd that i can download them in one line) 5- sudo a2enmod rewrite 6- sudo systemctl restart apache2

Checkpoint2: 1- cd ../../var/www/html 2- pwd 3- sudo git clone https://github.com/Soultaker707/stunning-laravel.git

Checkpoint3: 1- sudo curl -sS https://getcomposer.org/installer -o composer-setup.php | sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer (used double dash "--" instead of 1 big dash like in the file)

2- sudo composer install

Checkpoint4: 1- pwd 2- cp .env.example .env 3-4- vim .env.example (inside vim use :i to edit, :w to write and :x to exit) 5- php artisan key:generate

Checkpoint5:

1- apache2 -v 2- cd /etc/apache2 3- ls 4- used vim (same steps as before) 5- cd sites-enabled 6- used vim as before 7- sudo systemctl restart apache2

Checkpoint6: 1- cd ../../../var/www/html/stunning-laravel

2- “sudo chgrp -R www-data storage bootstrap/cache” sudo: explained before

chgrp: This is a command to change the group ownership of a file or directory. -R option to recursively change the group ownership of all files and directories in the storage and bootstrap/cache directories. www-data: This is the name of the group to which the ownership is being changed. storage bootstrap/cache: These are the directories whose group ownership is being changed.

3- “sudo chmod -R ug+rwx storage bootstrap/cache" sudo: ... chmod: This is a command to change the file mode or permission of a file or directory (read, write, execute). -R option to recursively change the permission of all files and directories in the storage and bootstrap/cache directories. ug+rwx: This is the permission mode being assigned to the directories. u stands for "user," g stands for "group," and rwx stands for "read, write, and execute." storage bootstrap/cache: These are the directories whose permission is being changed. T


ipAddress: 34.255.29.166

