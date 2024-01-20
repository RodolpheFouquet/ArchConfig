# How to install 

* Create a file containing the vault password named .vault_pass

* Run the following command
```
ansible-galaxy collection install -r requirements.yml
ansible-playbook --ask-become-pass local.yaml --vault-pass-file=.vault_pass
```
