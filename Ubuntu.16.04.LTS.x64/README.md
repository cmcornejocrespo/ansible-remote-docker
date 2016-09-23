# kubernetes-aws-ansible
Ansible playbook that installs in ubuntu (aws) kubernetes

# Requisitos de configuraccion para la conexion de Ansible a un servidor
Tener el certificado .pem del servidor en nuestro local y ejecutarle un chmod 400 sobre el, para que ansible pueda leerlo
Tener correctamente el remote_user y private_key_file del servidor remoto dentro de nuestro ansible.cfg
