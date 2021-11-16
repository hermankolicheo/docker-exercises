# PREGUNTA_N3

Ejecuta el siguiente comando para crear una imagen **mysql** con el nombre **mysql-zippy**, asignando el usuario **"zippy"**, la contraseña **"zippypass"** y una base de datos inicial llamada **dbzippy** para luego realizar una prueba de conexión con el puerto por defecto 3036

```bash
docker run --name mysql-zippy -e MYSQL_ROOT_PASSWORD="secret-pass" -e MYSQL_USER="zippy" -e MYSQL_PASSWORD="zippypass" -e MYSQL_DATABASE="dbzippy" -p 3036:3036 -d mysql:8.0
```
Ejecuta el siguiente comando para instanciar y probar la conexión a la base de datos creada anteriormente , usando el usuario creado **"zippy"** y la contraseña **"zippypass"**.
```bash
 docker exec -it mysql-zippy-1 mysql -uzippy -p
``` 
