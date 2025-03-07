# Ansible Collection - lxhome.ngnix

Documentation for the collection.

Important: Make sure the DNS record is added properly to the DNS provider !

## Execution
``` shell
    # to install 
    ansible-playbook -i inventory.ini main.yml -t install
    # to remove all files
    ansible-playbook -i inventory.ini main.yml -t purge
```