# Caso-de-Estudio_A
Caso de estudio con las playbooks de ansible

pagina_html:
playbook para el html se debe revisar la dirección ip y el tipo de conexion, esta por ssh sin contraseña
ansible-playbook -i /path/to/inventory html.yaml

studio_ansible y telnet son las playbooks para conexion ssh y telnet. revisar la dirección ip y el usuario y la contraseña para ssh
ansible-playbook -i /path/to/inventory playbook.yaml
