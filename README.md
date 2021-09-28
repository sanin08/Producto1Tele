# ST0263-jssaninv

# Titulo
Producto 1

# Autor
Juan Sebastián Sanín Villarreal

# Software
Certificado SSL wordpress: docker

# Descripción
Se implementó una pagina WEB desplegada en GCP la cual posee una certificación en SSL y es creada en wordpress

# Diseño
Se adquirio el dominio por medio de freenom, se creó la instancia de la VM en google cloud, se tiene el certificado SSL por medio del gitHub https://github.com/jmlcas/Docker-WordPress-SSL.git, también se tiene una ip V4 elastica en VPC de GCP, por ultimo se implementó el cloud DNS

# Instalación
1) Instalar git en cd home/jssaninv/ `sudo apt-get install git`
2) Intalar en la misma dirección docker.io docker-compose `sudo apt-get install docker.io docker-compose`
3) En la misma ruta clonar repositorio `git clone https://github.com/sanin08/Producto1Tele.git`
4) por ultimo Subir docker en la ruta home/jssaninv/Producto1Tele/web-wp `sudo docker-compose up -d`
# Ejecución
Utilizar cualquiera de las dos siguientes opciones en el buscador:
1) Dirección ip: https://35.192.190.16/
2) Poner el dominio: https://producto1topicoseafit.gq/
