.PHONY: install 

install:
	ansible-playbook playbooks/install.yml -i inventory.ini --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"

remove: 
	ansible-playbook playbooks/remove.yml -i inventory.ini --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"
