.PHONY: start

start: 
	ansible-playbook playbooks/main.yml -i inventory.ini --user=root \
                              --extra-vars "ansible_sudo_pass=rootpassword" -vvv

delete: 
	ansible-playbook playbooks/main.yml -i inventory.ini --user=root \
                              --extra-vars "ansible_sudo_pass=rootpassword" -vvv