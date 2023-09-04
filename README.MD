## NRPE Install 

This repository defines how to install nagios nrpe agent with an ansible. It's so simple, first create inventory file and define related variables. After run playbook.

```
ansible-playbook -i inventory nrpe.yml 
```