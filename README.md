# block15
rebrain ansible final task

:~/task$ ansible-playbook -i ~/task/inventory.yaml joomlaproject.yml -e "@~/task/joomla.vault" --vault-password-file .vault_pass
