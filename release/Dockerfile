FROM aaronpederson/ubuntu

RUN ansible-galaxy install telusdigital.nginx
COPY playbook.yml /etc/
RUN ansible-playbook /etc/playbook.yml
