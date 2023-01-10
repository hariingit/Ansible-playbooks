#########################################################################
Ansible playbook for kibana
#########################################################################
The Repo contains ansible-playbook to set up a kibana as a service.

To create a Role:
 ansible-galaxy init kibana

To Run the playbook:
 ansible-playbook -c local -i localhost, kibana.yml --extra-vars "update_apt_cache=false"
Setup nginx, kibana# Ansible-playbooks
