# 1. Partimos de Ubuntu
FROM ubuntu:latest

# 2. Actualizamos índices y paquetes
RUN apt-get update && apt-get upgrade -y

# 3. Instalamos Python 3 y pip3
RUN apt-get install -y python3 python3-pip

# 4. (Si hace falta) eliminamos la restricción de entorno gestionado
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

# 5. Instalamos Flask con pip3
RUN pip3 install flask
RUN pip3 install flask-cors


# 6. Definimos el directorio de trabajo dentro del contenedor
WORKDIR /app

# 7. Copiamos nuestro script Flask
COPY api.py /app/api.py

# 8. Al arrancar el contenedor, lanzamos la app Flask
CMD ["python3", "api.py"]
