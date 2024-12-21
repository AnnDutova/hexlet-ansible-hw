.PHONY: start

install:
	ansible-galaxy install -r requirements.yml

start: install
	ansible-playbook playbooks/main.yml -i inventory.ini --check --user=root --extra-vars "ansible_sudo_pass=ChangeMe" -vvv
	