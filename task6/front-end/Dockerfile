# 1. Partimos de la imagen oficial de Nginx
FROM nginx:latest

# 2. Copiamos el contenido estático al directorio que Nginx sirve por defecto
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# 3. Copiamos nuestra configuración personalizada de Nginx
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
