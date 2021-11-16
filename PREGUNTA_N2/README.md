# PREGUNTA_N2 

Con la imagen creada anteriormente y en el directorio raiz ejecutar el siguiente comando:
```bash
sudo docker run -v $PWD/:/usr/share/nginx/html -d -p 8080:80 zippy-img
```
Con este contenedor compartido podemos realizar cambios y las modificaciones al archivo **index.html** son bidireccionales.

Ejecute el siguiente comando para modificar el **index.html**
```bash
vim index.html
```  
O abra el archivo con su editor de código favorito, realiza algún cambio en el **index.html**, guarda el archivo y estos se verán reflejados, finalmente recarga la página para ver los cambios realizados.
