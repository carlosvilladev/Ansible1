# Configuración Ansible para Sitio en Moodle
Configuración de 3 máquinas Docker (Apache, Mysql, Redis)

### Construir las máquinas

- ./create_dockers.sh


### Recrear Dockers y Adicionar llaves SSH

- ./crean_all.sh


### Playbooks

- cd Ansible1/ansible001

- ansible-playbook -i ../hosts all.yml

