# Prepare Server(s) for Ansible (ansible-init)



If you are looking for the fast and reliable way how to copy your Ansible master server public SSH key to the newly deployed server(s), you came to the right place. This simple ansible-init playbook just takes <i>id_rsa.pub</i> SSH public key from default location and distribute it to the new server(s) based on described inventory information.

## init.ansible.yaml

used to prepare ssh keys in localhost and remote server


## provision.ansible.yaml

used to install dependencies and provide requirements


## initalizeProject.ansible.yaml

used to pull and start the code,
