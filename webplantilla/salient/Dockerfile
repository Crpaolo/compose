FROM nginx:alpine

WORKDIR /usr/share/nginx/html

# Borrar archivos por defecto de NGINX
RUN rm -rf ./*

# Copiar todos los archivos de la carpeta actual (webplantilla) al contenedor
COPY . .

# Exponer puerto 8081
EXPOSE 8081

CMD ["nginx", "-g", "daemon off;"]
