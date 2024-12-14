.PHONY: start

start: 
	ansible-playbook playbooks/main.yml -i inventory.ini --user=root --extra-vars "ansible_sudo_pass=ChangeMe" -vvv

delete: 
	ansible-playbook playbooks/main.yml -i inventory.ini  --user=root --extra-vars "ansible_sudo_pass=ChangeMe" -vvv
	