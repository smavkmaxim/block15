# block15
rebrain ansible final task

ansible-playbook -i /home/user/task/inventory.yaml  /home/user/task/joomlaproject.yml -e "@/home/user/task/joomla.vault" --vault-password-file /home/user/task/.vault_pass
