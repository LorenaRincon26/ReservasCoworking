**Instrucciones de Despliegue**

**Requisitos previos**

- Java 8 o superior
- Tomcat 9 o superior

**Pasos para el despliegue**

1. **Clonar el proyecto**: Clona el proyecto desde el repositorio Git utilizando el comando **git clone <url-del-repositorio>**.
1. **Configurar el entorno**: Asegúrate de tener Java y Tomcat instalados en tu máquina local. Si no los tienes, puedes descargarlos desde sus sitios web oficiales.
1. **Desplegar en Tomcat**: Coloca el archivo **war** del proyecto en la carpeta **webapps** de Tomcat. Puedes hacer esto manualmente o utilizando un IDE como Eclipse o IntelliJ IDEA.
1. **Iniciar Tomcat**: Inicia el servidor Tomcat utilizando el comando **startup.bat** (en Windows) o **startup.sh** (en Linux/Mac).
1. **Acceder a la aplicación**: Abre un navegador web y accede a la URL **http://localhost:8080/ProyectoReservaCoworking/index.html** para acceder al formulario de reservas.

**Acceso a la aplicación**

La URL predeterminada para acceder al formulario de reservas es **http://localhost:8080/ProyectoReservaCoworking/index.html**. Si deseas desplegar la aplicación en una nube de desarrollo, debes reemplazar **localhost** con la dirección IP o el nombre de dominio de tu servidor.

**Notas**

- Asegúrate de que el puerto 8080 esté disponible en tu máquina local. Si no es así, puedes cambiar el puerto en el archivo **server.xml** de Tomcat.
- Si tienes problemas para desplegar la aplicación, verifica que tengas los requisitos previos instalados correctamente y que el archivo **war** esté en la carpeta correcta.

