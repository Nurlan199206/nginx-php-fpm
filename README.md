# nginx-php-fpm installation on Ubuntu.

Software version.

Ansible 2.7

Ubuntu 18.04

php 7.2

nginx 1.14


run command: ansible-playbook -i /etc/ansible/roles/nginx-php-fpm/defaults/static.cfg --connection=local -s /etc/ansible/roles/nginx-php-fpm/nginx.yml

for successfully run playbook, dont forget add in /etc/ansible/ansible.cfg after [defaults]

invalid_task_attribute_failed=False
