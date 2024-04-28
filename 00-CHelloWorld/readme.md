# Trabajo Práctico #0 : "Hello, World!" en C

### 3.1. Objetivos
+ Demostrar capacidad para editar, compilar, y ejecutar programas C mediante
el desarrollo de un programa simple.
+ Tener un primer contacto con las herramientas necesarias para abordar la
resolución de los trabajos posteriores.
### 3.2. Temas
+ Sistema de control de versiones.
+ Lenguaje de programación C.
+ Proceso de compilación.
+ Pruebas.
### 3.3. Problema
Adquirir y preparar los recursos necesarias para resolver los trabajos del curso.
### 3.4. Restricciones
+ Ninguna.
### 3.5. Tareas
1. Cuenta en GitHub
    - a. Si no tiene, cree una cuenta GitHub.
    - b. Si no lo hizo, asocie a su cuenta GitHub el email @frba y verifíquelo. Es posible asociar más de una cuenta email a una cuenta GitHub.
    - c. Si no lo hizo, indique que su cuenta email @frba es pública. Esto permite a la cátedra encontrar a los estudiantes. Si por temas de privacidad prefiere no tener como pública esa dirección, puede cambiarla al final del proceso.
2. Repositorio para público para la materia
    - a. Cree un repositorio público llamado SSL.
    - b. En la raíz de ese repositorio, escriba el archivo readme.md que actúa como front page del repositorio personal.
    - c. Cree la carpeta 00-CHelloWorld.
    - d. En esa carpeta, escriba un segundo archivo readme.md que actúa como front page de la resolución.
3. Compilador
    - a. Seleccione, instale, y configure, y pruebe un compilador C11 ó C18. Los más osados pueden buscar un compilador que soporte C2x.
    - b. Registre los resultados anteriores de la siguiente manera:
          -i. Indique en el readme.md el compilador seleccionado.
          - ii. Pruebe el compilador con un programa hello.c que envíe a stdout la línea Hello, World! o similar.
          - iii. Ejecute el programa y verifique que la salida es la esperada.
          - iv. Ejecute el programa con la salida redireccionada a un archivo output.txt; verifique su contenido.

## Resolución

1. Se escribió en lenguaje C lo necesario para que, en la salida, envíe "Hello World"
2. Se seleccion el nombre del programa y compilador c18 escribiendo en la terminal 
    ```
    gcc hello.c -o hello.exe -std=c18
    ```
3. Se redireccionó la ejecución del programa al archivo output.txt escribiendo en la terminal
    ```
    ./hello.exe > output.txt
    ```
