.PHONY: update

update: 
	ansible-playbook --check playbooks/main.yml -i inventory.ini -t update --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"

create: 
	ansible-playbook --check playbooks/main.yml -i inventory.ini -t create -vv --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"

install: 
	ansible-playbook --check playbooks/main.yml -i inventory.ini -t install --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"
							  
delete: 
	ansible-playbook --check playbooks/main.yml -i inventory.ini -t delete --user=root \
                              --extra-vars "ansible_sudo_pass=ChangeMe"