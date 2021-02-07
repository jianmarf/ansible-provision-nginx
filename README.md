This project uses vagrant ansible provision to install and run nginx container.

Files Included:

README.md

Vagrantfile

provision/playbook.yml

provision/roles/nginx/tasks/install-run-nginx.yml

Deployment Steps:

git clone https://github.com/jianmarf/ansible-provision-nginx.git

vagrant up

check nginx: curl http://localhost:8085
  
