# 1. FROM ubuntu:latest
#    Le dice a Docker: “quiero que uses como base la última imagen oficial de Ubuntu”.
FROM ubuntu:latest

# 2. RUN apt-get update
#    Actualiza la lista de paquetes disponibles en APT.
RUN apt-get update

# 3. RUN apt-get upgrade -y
#    Sube la versión de todos los paquetes instalados.
RUN apt-get upgrade -y

# 4. CMD ["echo", "Hello, World!"]
#    Define el comando que se ejecutará por defecto cuando arranque el contenedor.
CMD ["echo", "Hello, World!"]
