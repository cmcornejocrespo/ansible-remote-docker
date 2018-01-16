# Ubuntu.16.04.LTS.x64
Ansible playbook that installs in Ubuntu 16.04

# Requisitos de configuraccion para la conexion de Ansible a un servidor
Tener el certificado .pem del servidor en nuestro local y ejecutarle un chmod 400 sobre el, para que ansible pueda leerlo

Tener correctamente el remote_user y private_key_file del servidor remoto dentro de nuestro ansible.cfg

Tener instalado en el destino python-simplejson, va como primer paso de la ejecucion por si acaso:
```shell
$ apt install -y python-simplejson
```    
  

# Execute
ansible-playbook main.yml -vvvv

