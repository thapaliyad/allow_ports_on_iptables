# Author: Dhirendra Thapaliya
# E-mail: dev.ops.dhiru@gmail.com
# GitHub: https://github.com/thapaliyad

Name of the playbook: allow_ports_on_iptables
DescriptionL Basic ansible playbook which opens additional ports in the Linux (CentOS / RHEL 6/7 ) systems.

# How to use this script
1. clone the git repo (https://github.com/thapaliyad/allow_ports_on_iptables_with_ansible.git)
2. open vars/main.yml and change the variable values per your need. and 
3. run the playbook:
   ansible-playbook -i '-inventory-hostname-' open-ports-iptables.yml -K
   (provide the become password if prompted)
