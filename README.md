# Práctica 4 - Creación de un App Service

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 2 - Sesión 4

En esta práctica se realizó una página web con App Service.

-------------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.
- [Visual Studio Code](https://code.visualstudio.com/download).
- [Node.js](https://nodejs.org/es/download/)
- [Git Bash](https://git-scm.com/downloads)

-------------------------------------------------------------

#### Pasos a seguir

1. Ingresar a portal.azure.com y busca ‘App Service’ y pulsamos en ‘Crear’. De la misma manera que en las prácticas anteriores, creamos un nuevo grupo de recursos (o se puede seleccionar uno ya creado) y le damos un nombre a la instancia (por ejemplo: PaginaRestaurante). En ‘Pila del entorno en tiempo de ejecución’ seleccionamos ‘PHP 8.0’ y de región usamos central US (o cualquier otra región). Finalmente, en ‘SKU y tamaño’ escogemos el que sea gratis. Le damos en ‘Revisar y Crear’ y en ‘Crear’.

![P4I1](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2001.PNG)

2. Ingresamos al siguiente link: [https://github.com/josejesusguzman/lab-subir-app-service-azure](https://github.com/josejesusguzman/lab-subir-app-service-azure) y aquí en el apartado que diga ‘<>Code’ copiamos en el apartado SSH el escrito (debemos tener git instalado al igual que Node.js, en el mismo link viene los requisitos que necesitamos cumplir).

![P4I2](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2002.PNG)

3. En el explorador de archivos, ingresamos a nuestra carpeta que tengamos para guardar los documentos del curso de Innovacción Virtual y en la pestaña de ruta (la que está al lado izquierdo de la pestaña de búsqueda) escribimos ‘cmd’ y damos enter.

![P4I3](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2003.PNG)

4. Dentro de esta cmd, escribimos: git clone “escrito SSH copiado anteriormente” y se va a descargar un folder.

![P4I4](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2004.PNG)

5. En VisualStudio Code, abrimos ese folder (‘Open Folder’) que acabamos de descargar desde cmd, donde veremos varios archivos, y entre ellos, un archivo .md que se llama README, el cual contiene instrucciones.

![P4I5](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2005.PNG)

6. Ahora, regresamos al portal de Azure, donde habíamos creado el servicio de App Service, y le damos en ‘Ir al recurso’, y aquí mismo, nos dirigimos al apartado de ‘Centro de implementación’ y en el apartado donde diga ‘Origen’ seleccionamos ‘GitHub’. Nos logueamos con nuestra cuenta de GitHub, en ‘Organización’ colocamos nuestro usuario, ‘Repositorio’ el que acabamos de descargar y en ‘Rama’ colocamos main. Habiendo realizado eso, le damos en ‘Guardar’.

![P4I6](https://github.com/AlbertoSF99/Practica-4/blob/main/Images/Sesi%C3%B3n%204%20-%20P4%2006.PNG)

7. Ingresamos al siguiente link: [https://github.com/josejesusguzman/paginamuestraazure](https://github.com/josejesusguzman/paginamuestraazure) y en la pestaña de ‘action’ podremos ver la ejecución en tiempo real de la página creada con App Service, por lo que se deberá esperar unos minutos para que se termine de crear.

8. Después de haber esperado un rato, vamos al workflow y clickeamos sobre ‘Add or update the Azure App Service build and deploy…’ y en el apartado de ‘Deploy’ habrá un link desde el que podemos acceder a la página web creada.

***Información Adicional:*** El proceso que creamos del App Service cobra por hora, por lo que es importante detenerlo cuando ya no se necesite. Con el tipo de “suscripción free” solo podremos mostrar la página web 60 minutos por cliente cada día. Si no deja descargar el repositorio con el link SSH, intentar con el link HTTPS.
