# tddIcEspe
Ejemplo de TDD en Código de Infraestructura  - ESPE 2018

## serverSpec101
Para utilizar el codigo se necesita:

  * Ansible 2.2 o superior
  * ServerSpec 2.0 o superior
  * Servidor RHEL/CentOS de nombre sriapp04

## Ejecutar:
Para ejecutar el playbook

´ansible-playbook main.yml -i inventory -e "target=test"´

Para ejecutar las pruebas en la carpeta del rol a probar

´rake spec´