# IAW
## Descargando e instalando Docker ##
# Realizado por: Juanma Martin Delgado #

![Imagen 1](1.png)

Lo primero será buscar en el navegador de google chrome el ejecutable de docker.exe para Windows en mi caso

![Imagen 2](2.png)

Con este comando podremos ver las diferentes distribuciones que podemos descagar e instalar como subsistema linux en nuestro Windows

![Imagen 3](3.png)

Vamos a instalar uno deseado, como el Ubuntu

![Imagen 4](4.png)

Ya tenemos instalado el subsistema Linux ubuntu

![Imagen 5](5.png)

Una vez tengamos todo lo anterior, ejecutamos docker para poder crear una cuenta nueva

![Imagen 6](6.png)

Ya tan solo cuando hayamos creado la cuenta, iniciamos sesión, y nos aparecerá la ventana de inicio de docker.


# IAW
## Descargando, inspeccionando y borrando imágenes en Docker ##
# Realizado por: Juanma Martin Delgado #

![Imagen fo1](fo1.png)

Lo primero será descargar la imagen de Ubuntu 20.04 con el comando docker pull

![Imagen fo2](fo2.png)

Con este comando guardaremos los datos de la imagen en el archivo info.txt

![Imagen fo3](fo3.png)

Vamos a crear un contenedor llamado modulo3 a partir de la imagen y a entrar en su terminal

![Imagen fo4](fo4.png)

Si intentamos borrar la imagen no nos deja, ya que el contenedor modulo3 la sigue usando aunque esté parado

![Imagen fo5](fo5.png)

Por eso borramos primero el contenedor modulo3 con docker rm

![Imagen fo6](fo6.png)

Una vez borrado el contenedor, ya podemos borrar la imagen de Ubuntu 20.04 con docker rmi
