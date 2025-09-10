# Imagen base de NGINX
FROM nginx:alpine

# Directorio de trabajo por defecto de NGINX
WORKDIR /usr/share/nginx/html

# Limpiar archivos por defecto
RUN rm -rf ./*

# Copiar tu plantilla al contenedor
COPY ./webplantilla/ .

# Exponer el puerto 8081
EXPOSE 8081

# Configurar NGINX para escuchar en 8081
CMD ["nginx", "-g", "daemon off;"]
