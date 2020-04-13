# **ACTIVIDADES DE PROGRAMACION**
## *Alumno: Lucas Matías Quiroga*
## *Carrera: Desarrollo de Software*
- - - 
# *Introducción a Git (Github/Gitlab)*

# ***1) Que es Git?***
Git es un software de control de versiones, que administra las distintas versiones de un programa. El mismo fue ideado por Linus Torvals.

# ***2) Por qué queremos utilizar Git?***
Queremos utilizar Git para administrar y poder controlar los cambios en nuestro sistema, administrar la complejidad del mismo, como asi también trabajar en proyectos personales y/o con otros desarrolladores, de manera profesional. El mismo tiene un control de los cambios realizados en conjunto con la fecha de los mismos. Facilita cuando uno quiere retomar alguna linea mas ordenada del codigo que estamos desarrollando.

# ***3) Qué es el Bash que instala Git?***
Es una herramienta que permite gestionar todos los cambios del proyecto a realizar. Funciona en todos los sistemas operativos.

# ***4) Describa los estados:*** 
- **Working directory** 
- **Staging area** 
- **Repository**

1- Working Directory:  Es donde uno trabaja con los archivos del programa.
2- Staging Área: Es donde se agregan todos los archivos que vas a preparar para el guardado.
3- Repository: Cuando uno esta decidido a realizar el guardado de los archivos, se pasa al repository.

# ***5) Describa el flujo para crear un nuevo repositorio git.***
Antes de empezar, creamos una carpeta con un nombre en particular (en el ejemplo del video lo hace en el escritorio y con el nombre proyecto).

Para inicializar dicho repositorio, usa 3 formas.
1) Abrir la carpeta con el botón derecho y elegir la opción 
**"Git Bash Here"**

2) Usar el ejecutar del sistema operativo (cmd) y dentro del mismo seguir estos pasos:
- primero nos situa donde se encuentra actualmente.
- Luego ejecutamos cd desktop y nos cambia al escritorio.
- Por ultimo, estando dentro de la carpeta proyecto del escritorio, hacemos cd + nombre del proyecto.

3) Abrimos la consola de Git Bash.
- Escribimos pwd y nos muestra el directorio actual.
- Ejecutamos cd desktop e ingresamos al escritorio.
- Luego ejecutamos cd + nombre del proyecto.
- Ahora colocamos ls y nos muestra que en dicha carpeta, hay 2 archivos.
- Por ultimo, escribimos git init y podemos inicializar un proyecto.

# ***6) Describa el flujo para agregar un archivo simple al repositorio.***
Para agregar un archivo simple al repositorio, debemos seguir estos simples pasos:
- Luego de ejecutar git init, lo que hacemos es escribir git status y muestra los archivos que no se han agregado (estan como en el aire).
- Entonces con git add -file- + el nombre de/l archivo/s podemos agregarlos al staging área.
- Ahora ejecutamos git commit (permite crear el punto de partida de nuestro código). Nos muestra un cartel que dice quien eres tu?, paso seguido vamos a configurar nombre y el e mail.
- Con estos comandosGit config -- global user.mail agregamos nuestro correo electronico y con git config--global user.name, escribimos nuestro nombre (asociamos estos datos al proyecto).
- Nuevamente ejecutamos git commit (punto de partida o foto de nuestro proyecto), abriendose un editor de código llamado bin.

# ***7) Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.***
Lo primero que debemos hacer, es generar un cambio en el archivo. Luego con git status, muestra que hubo modificaciones en el mismo. Entonces, al usar git diff, que permite ver los cambios generados en los archivos, pero se debe agregar. Ejecutamos nuevamente git add + el nombre del archivo, git status (vemos el estado de los archivos) guardamos los cambios con git commit. Por último, para visualizar todos los cambios que se realizaron, se ejecuta texto + qw.

# ***8) ¿Cómo hago para ignorar un archivo o carpeta?***

Para ignorar un archivo o carpeta, lo que debemos hacer es ejecutar git ignore + el nombre del mismo.

# ***9)Explique que es un Branch. Dé un pequeño ejemplo de como haría uno.***

Branch es un atajo que permite crear versiones opcionales al proyecto que estamos realizando.
Para crear uno, lo que podemos hacer es escribir git branch + el nombre de la carpeta, entonces me aparece por defecto master y el que nombramos anteriormente. Con git checkout salimos de uno e ingresamos a la otra.

# ***10) Que es Git add?***

Git add es un comando que me permite pasar de working directory a staging area.

# ***11) ¿Cómo cambiamos de un brach a otro?***

Para cambiar de un brach a otro, escribimos el comando git checkout + nombre del branch y ya estariamos dentro de otro (que por defecto lo nombra master).

