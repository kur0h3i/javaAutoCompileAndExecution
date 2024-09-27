# javaAutoCompileAndExecution


This repository contains a Bash script that automates the process of compiling and executing Java files. It is ideal for developers working on small Java projects who want a quick and easy method to compile and run their code without needing to manually enter multiple commands.
Description

The script checks if there is a file named Main.java in the current directory. If the file exists, the script will compile all .java files in the directory using javac, and then it will execute the Main.class file using java.
Script Flow:

    Verification of Main.java: The script starts by checking if the Main.java file is present in the current directory.

    Compilation of Java Files: If Main.java exists, all files with the .java extension in the current directory will be compiled using javac.

    Execution of Main.class: After compilation, the script will execute the Main class if the compilation was successful.

    Error Handling: If the Main.java file is not present in the directory, the script will display an error message indicating that the file does not exist.


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Este repositorio contiene un script de Bash que automatiza el proceso de compilación y ejecución de archivos Java. Es ideal para desarrolladores que trabajan en pequeños proyectos Java y desean un método rápido y sencillo para compilar y ejecutar su código sin necesidad de múltiples comandos manuales.
Descripción

El script comprueba si existe un archivo llamado Main.java en el directorio actual. Si el archivo existe, el script compilará todos los archivos .java en el directorio usando javac y luego ejecutará el archivo Main.class utilizando java.
Flujo del Script:

    Verificación de Main.java: El script comienza verificando si el archivo Main.java está presente en el directorio actual.

    Compilación de Archivos Java: Si Main.java existe, todos los archivos con la extensión .java en el directorio actual serán compilados mediante javac.

    Ejecución de Main.class: Después de la compilación, el script ejecuta la clase Main si la compilación fue exitosa.

    Manejo de Errores: Si el archivo Main.java no está presente en el directorio, el script muestra un mensaje de error indicando que el archivo no existe.
