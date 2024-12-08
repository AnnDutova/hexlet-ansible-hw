.PHONY: ping-all

ping-all: 
	ansible all -i inventory.ini -u root -m ping

ping-first:
	ansible first -i inventory.ini -a 'uptime'

ping-by-name:
	ansible all --limit server_test1 -i inventory.ini -m ping