# EvidenciaFinal
• Instalación y configuración. 
El programa debe ser instalado mediante el JAR que se encuentra en GitHub.
Se configurara inicialmente el usuario y la contraeña
• Uso del programa. 
una vez que se tiene ya cargado el usuario y la contraseña se debe reiniciar el proyecto. Debe utilizarse el menu con numeros enteros, todos los demas datos son
String y seran los datos que contendran las instancias de las clases.
• Créditos. 
Luis Felipe Bravo Hernandez
• Licencia. La documentación de la aplicación se debe manejar en GitHub en el área de Wiki y las secciones con las que debe contar son: 
• Acerca de: se explica brevemente la aplicación. 
La aplicacion tiene un menu general para realizar acciones como añadir doctores, pacientes y citas, asi como para relacionarlas.
• Proyecto: incluir el diagrama de flujo en la entrega uno, además de describir cada una de las clases incluidas, su propósito y descripción de sus métodos y variables. 
Enlace a diagrama de flujo https://utmedu-my.sharepoint.com/:i:/g/personal/al02914746_tecmilenio_mx/ER1wrdo6VJpOjA14LIvZBUYBTvTKrl8_DsxZb6wB9CGdJg?e=3QETu7
• Guías: pasos para configurar, ejecutar el programa, y crear un JAR ejecutable desde el código almacenado en el repositorio. 
Pasos para crear un JAR desde IntelliJIdea
Archivo -> Estructura del proyecto ...
Configuración del proyecto -> Artefacto en la columna izquierda
"+" en la columna central -> JAR -> Vacío -> Escriba el nombre
Haga clic en el nombre creado en la columna central
Diseño de salida (columna derecha) -> "+" (Añadir copia de)-> Contenido del directorio Si su archivo .class está en com.myprojects.myfirstproject, debe crear la carpeta "com" en la raíz de jar, la carpeta "myprojects" en la carpeta "com", "myfirstproject" en la carpeta "myprojects"
"+" -> Archivo -> seleccione sus archivos .class de com.myprojects.myfirstproject
Crear archivo de manifiesto en la raíz de jar
Especifique la clase principal como "com.myprojects.myfirstproject.Main"
Aplicar
