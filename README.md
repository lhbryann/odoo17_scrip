# Odoo 17

Módulos base de Odoo ERP

## Desplegar proyecto
docker-compose up -d 
## lanzar la instancia
docker ps
## intancias lanzadas
docker exec {nombre_contenedor} /usr/bin/odoo scaffold {nombre_modulo} /mnt/extra-addons
## creacion de un modulo
docker exec -it {nombre_contenedor} /usr/bin/odoo -d {nombre_db} -u {nombre_modulo}
## actualizar (upgrade) un módulo específico de Odoo dentro de un contenedor Docker

## extras
Odoo Debug -- google extencion
Odoo Snippets -- vscode

