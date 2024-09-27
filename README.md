# javaAutoCompileAndExecution

Este repositorio contiene un script de Bash que automatiza el proceso de compilación y ejecución de archivos Java. Es ideal para desarrolladores que trabajan en pequeños proyectos Java y desean un método rápido y sencillo para compilar y ejecutar su código sin necesidad de múltiples comandos manuales.
Descripción

El script comprueba si existe un archivo llamado Main.java en el directorio actual. Si el archivo existe, el script compilará todos los archivos .java en el directorio usando javac y luego ejecutará el archivo Main.class utilizando java.
Flujo del Script:

    Verificación de Main.java: El script comienza verificando si el archivo Main.java está presente en el directorio actual.

    Compilación de Archivos Java: Si Main.java existe, todos los archivos con la extensión .java en el directorio actual serán compilados mediante javac.

    Ejecución de Main.class: Después de la compilación, el script ejecuta la clase Main si la compilación fue exitosa.

    Manejo de Errores: Si el archivo Main.java no está presente en el directorio, el script muestra un mensaje de error indicando que el archivo no existe.
