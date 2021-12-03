INSTALACIÓN Y CONFIGURACIÓN

¿Cómo ejecutar el programa? Una vez descargado o clonado el proyecto se puede ejecutar el programa de dos maneras diferentes.

Utilizando IDE
Utilizando la consola
-Utilizar un IDE:

Descomprimir el proyecto. (Hay que saber en qué ubicación lo estamos descomprimiendo para futuros pasos).
Abrir el IDE de tu elección (NetBeans, Eclipse, InteljiJ).
En caso de ser NetBeans, seleccionar la opción "Open Proyect..." del menú "File". En caso de no encontrarse en NetBeans, seleccionar la opción correspondiente a "Abrir proyecto".
Se abrirá una ventana en la que seleccionaremos nuestra carpeta. En este punto, hay que buscar la ruta en que se descomprimió el proyecto, para poder abrirlo. La carpeta debería aparecer con un ícono de una taza de café (ícono de Java), esa es la que se seleccionará.
Ya con el proyecto abierto en NetBeans, se selecciona el botón con el ícono de reproducción (Run) para correr el programa. Entonces se despliegará el resultado en la consola integrada de NetBeans.
-Utilizar la consola: Para este procedimiento, es necesario contar con el archivo ejecutable .JAR, de lo contrario no servirá.

Descomprimir el proyecto. (Hay que saber en qué ubicación lo estamos descomprimiendo para futuros pasos).
Abrir la consola (Símbolo del sistema).
Dirigirnos a la ruta en que está el ejecutable (en la carpeta "dist" del proyecto), por medio de comandos (cd /dist).
Escribir el siguiente comando: java -jar "Evidencia.jar". Esto nos permitirá la correcta ejecución del programa, desde la consola.
USO DEL PROGRAMA

Para usar el programa, hay que iniciar sesión con un usuario registrado en la base de datos.

El usuario inicial o provisional, con el que se puede probar el funcionamiento es: *Usuario: testUser *Contraseña: passwordUser

Una vez iniciada sesión, para realizar las diferentes funciones hay que seguir las instrucciones del menú interactivo:

Dar de alta paciente: registrar el paciente por medio de su ID, nombre y una bereve descripción del problema que lo trajo.
Mostar pacientes: lista todos los pacientes de la base de datos y sus atributos
Dar de alta doctor: registra el doctor mediante su ID, nombre y especialidad.
Mostrar doctores: lista todos los doctores en la base de datos y sus atributos.
Agendar cita: crea una lista con ID, fecha y hora.
Mostrar todas las citas: lista todas las citas con sus respectivos atributos.
Relacionar citas: toma los IDs de la cita, doctor y paciente como parámetros y las relaciona en la base de datos.
Mostrar citas relacionadas: muestra todas las citas con su respectivo doctor, fecha y paciente.
(0)Salir: termina la ejecución del programa.
CRÉDITOS

Desarrollado por Daniel Goyzueta

LICENCIA

Copyright 2021 Daniel Goyzueta

