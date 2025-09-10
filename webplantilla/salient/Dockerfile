FROM nginx:alpine
WORKDIR /usr/share/nginx/html

# Limpiar lo que viene por defecto
RUN rm -rf ./*

# Copiar todo tu contenido de la plantilla
COPY . .

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
