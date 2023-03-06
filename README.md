# Install Certificate Authority
'install_ca.yaml' is a playbook that install all given certificates in the 'files/ca' folder.

## Usage
Since it's not a role but a "simple" playbook you can execute it by using the ansible bin.
```bash 
ansible-playbook -i 'inventory_file' -K 'install_ca.yaml'
```
> Note that '-K' is *MANDATORY* since the playbook uses '*become*'.