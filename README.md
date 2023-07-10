# Curso Upskilling Henry 
#Microservicios usando Docker Compose


Creación de microservicios usando Dockker, Docker-Compose y dedployando a virtual machines
Dispone de 5 microservicios: 
- gatewway
- Characters
- Films
- Planets
- database
Database es una base de datos noSql (en MongoDb Atlas) desde donde realizan consultas los microservicios character, films y planets.
Gateway ofrece un unico puerto de acceso (8000), ocultando llos puertos de los resttantes microservicios.
Database no forma parte del gateway, sino que se conecta mediante una network generada por compose.

