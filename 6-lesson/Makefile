.PHONY: start

start: 
	ansible-playbook playbooks/main.yml -i inventory.ini -t install --user=root --extra-vars "ansible_sudo_pass=ChangeMe" -vvv

delete: 
	ansible-playbook playbooks/main.yml -i inventory.ini -t delete --user=root --extra-vars "ansible_sudo_pass=ChangeMe" -vvv