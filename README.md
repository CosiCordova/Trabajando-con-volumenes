# Trabajando-con-volumenes
# 1. Descarga la imagen 'httpd' y comprueba que está en tu equipo.

La imagen se descarga con el siguiente comando: "docker pull httpd" y se puede comprobar en el apartado de docker  del Visual Studio Code donde se encuentra la carpeta de images la cual al abrir lleva los nombres de todas las imagenes descargadas.

# 2. Crea un contenedor con el nombre 'asir_httpd'.
# 3. Mapea el puerto 80 del contenedor con el puerto 8000 de tu máquina.
    
 Para crear un contenedor (asir_httpd) y mapear el puerto 80 con el puerto 800 de tu maquina aplicamos el siguinete comando: docker run -dit --name asir_httpd -p 800:80 httpd:2.4

 Para confirmar que funciona correctamente es necesario ingresar en el busacador de preferencia y colocar "localhost:800" si el procedimientop fue el adecuado dara como resultado el texto "It works!"
