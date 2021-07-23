default: run

run:
	docker-compose up

prepare:
	sudo usermod -a -G docker $USER
	sudo systemctl start docker
	sudo systemctl enable docker

ssh:
	docker exec -it odoo_14 /bin/bash
