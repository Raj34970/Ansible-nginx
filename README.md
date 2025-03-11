# Ansible Collection - lxhome.ngnix

Documentation for the collection.

Important: Make sure the DNS record is added properly to the DNS provider !

## Execution
``` shell
    # to install 
    ansible-playbook -i inventory.ini main.yml -t install
    # to remove certain files
    ansible-playbook -i inventory.ini main.yml -t purge
    # to remove all files
    ansible-playbook -i inventory.ini main.yml -t purge_all
```