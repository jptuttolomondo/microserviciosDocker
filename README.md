# Curso Upskilling Henry 
#Microservicios usando Docker Compose


Creación de microservicios usando Dockker, Docker-Compose y dedployando a virtual machines
Dispone de 5 microservicios: 
- gatewway
- Characters
- Films
- Planets
- database

Database es un microservicio que utiliza una base de datos noSql (en MongoDb Atlas) desde donde realizan consultas los microservicios character, films y planets.
Gateway ofrece un único puerto de acceso (8000), ocultando los puertos de los restantes microservicios.
Database no forma parte de gateway, sino que se conecta mediante una network generada por compose.

