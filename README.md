# Odoo 17

Módulos base de Odoo ERP

docker-compose up -d 

docker ps

docker exec {nombre_contenedor} /usr/bin/odoo scaffold {nombre_modulo} /mnt/extra-addons

docker exec -it {nombre_contenedor} /usr/bin/odoo -d {nombre_db} -u {nombre_modulo}
