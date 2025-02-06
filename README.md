# ansible-promtail
This setup automates the process of configuring your server to send logs to Grafana Loki server using Ansible.

****Steps:****\
1- Install Ansible.\
2- clone this repo and modify the files to add your specific IP addresses (target and loki server).\
3- execute: $ ansible-playbook -i inventory.yaml playbook.yaml\
