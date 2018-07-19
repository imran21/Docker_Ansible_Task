# Docker_Ansible_Task
This Repository Contains the Docker and Ansible code for the task mentioned in Task_question file.

The Repository Contains two part. Part 1- Docker Part 2- Ansible

NOTE : As this codes runs on Amazon EC2 Machine, so the Public IP address of the machine should be noted down to change in configuration file before executing the task. It applies for both task.


After successfully running those task you can check through curl

curl -I 54.245.220.141
curl -I 54.245.220.141:8080
curl --raw 54.245.220.141
curl --raw 54.245.220.141:8080
curl --I 54.245.220.141:8080/protected
curl --I 54.245.220.141:8080/unprotected
curl --raw 54.245.220.141:8080/php_info_test.php
