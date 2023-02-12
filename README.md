# redhat_docker_setup.yml

Ansible Playbook to install docker on CentOS, Fedora, or any other Red Hat based Linux distribution

The playbook in summary will do the following:
1. Install docker
2. Start docker
3. Enable docker
4. Install docker-py
5. Pull httpd image from docker hub
6. Run httpd container
7. Copy index.html to the container
8. Copy httpd.conf to the container
9. Restart httpd
