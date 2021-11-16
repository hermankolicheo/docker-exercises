# PREGUNTA_N1
### ¡Hello Zippy!

Hello Zippy es un archivo HTML ejecutado en un contenedor Docker con Nginx.

## Instalación

> 1. Crea la imagen según la receta Dockerfile. Opcionalmente puede asignar una nueva etiqueta en  "zippy-img" 
```bash
docker build -t zippy-img .
```

## Despliegue
> 1. Luego ejecuta el siguiente comando para desplegar un contenedor de la imagen creada anteriormente exponiendo el puerto de escucha 80. (Insertar etiqueta correspondiente).
```bash
docker run -d -p 8080:80 zippy-img
```
