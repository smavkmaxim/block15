# block15
rebrain ansible final task

ansible-playbook -i ~/task/inventory.yaml  ~/task/joomlaproject.yml -e "@~/task/joomla.vault" --vault-password-file ~/task/.vault_pass
