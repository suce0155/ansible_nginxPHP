# Simple Ansible playbook to automatically setup Nginx and PHP. 

## Usage
1) Install Ansible. (apt install ansible)
2) Clone the repository.
3) Execute ansible-playbook -i inventory/hosts site.yml
4) If everything went correctly, info.php file is hosted on localhost/info.php

## Tasks
-Install Nginx

-Create Nginx log directory

-Create web root directory

-Configure Nginx

-Create vhost configuration

-Enable vhost

-Install PHP

-Ensure PHP is running

-Create test info.php file

-Restart Nginx
