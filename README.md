# Imagenes - Fronted y Backend
### Proyecto de criptografia utilizando RSA y AES

### Pasos para ejecutar los Dockerfile
1. Contar con los proyectos tanto del front como del backend
2. Mover el Dockerfile respectivo a cada proyecto y quitar el sufijo Front/Back
3. Mover cada Dockerfile a su respectivo proyecto
4. Ejecutar el comando `docker build -t <nombre_imagen> .` en cada proyecto
5. Ya con las imagenes creadas, ejecutar el comando `docker-compose up` en la carpeta raiz del proyecto
6. En la consola apareceran los logs de los contenedores, para ir a la pagina del fronted ir a localhost y para ir a la pagina del backend ir a 127.0.0.1:8000

### Pasos para usar las imagenes de DockerHub
1. Ir al docker-compose.yml y cambiar el nombre de las imagenes por las que se encuentran en DockerHub
2. La imagen para el fronted es: ovegero/proyecto-interciclo:front
3. La imagen para el backend es: ovegero/proyecto-interciclo:back
4. Ejecutar el comando `docker-compose up` en la carpeta donde se encuentre el docker-compose.yml
5. En la consola apareceran los logs de los contenedores, para ir a la pagina del fronted ir a localhost y para ir a la pagina del backend ir a 127.0.0.1:8000
