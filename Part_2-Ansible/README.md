# Configuring Httpd and Nginx through Ansible scripts

Before Running the ansible scripts give the Ip address of the host machnine in the nginx.conf file.

To run ansible playbook, type the following command

ansible-playbook task_run.yml

To run the ansible playbook with tag name 

ansible-playbook task_run.yml --tags <Tag_Name>

The List of Tags for httpd
* copy-httpd-conf
* copy-httpd-web-root
* copy-httpd-htpasswd
* start-httpd

The List of tags for nginx
* nginx-rootdir-template-reflect
* nginx-conf-template-reflect
* nginx-start
