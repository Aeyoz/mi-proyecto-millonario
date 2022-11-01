# mi-proyecto-millonario

Repositorio para la 3ª actividad de manipulacion de repositorios

Se han usado los comandos siguientes para la creación de este archivo:

+ cd $HOME/mi-proyecto-millonario/
+ touch README.md

Se usaran los siguientes comandos de la herramienta de git para subir los cambios a Github

+ git add 
+ git commit -m "Commit inicial"
+ git status
+ git push origin master/main


#### Pregunta: Si has clonado el repositorio ¿Qué parte del comando git push origin master se puede omitir?

Se puede omitir la parte de origin master, ya que la rama por defecto en github se establece como main, cosa que ya no se podría cambiar, y el origen es la nube, no nuestro equipo.

#### Pregunta:  ¿El fichero y el directorio privado se subiran al repositorio en la nube si están añadidos en el fichero .gitignore?

No, no se deberían de subir al repositorio que tengamos en la nube, ya que este fichero especifica que estos archivos se deben de ignorar.

#### Pregunta: ¿Qué realizan las acciones git add  y git commit sobre los ficheros?

Git add guarda los cambios que se hayan realizado a los ficheros del repositorio mientras que git commit les pone un comentario a modo de cabecera.

#### Pregunta: ¿Qué es un tag sobre un repositorio git, en nuestro caso Github?

Es una manera de etiquetación sobre estados de repositorios, normalmente se usa para especificar la versión actual del programa que el reposotirio contiene

#### Pregunta: ¿Cuál es el fin de trabajar en ramas? ¿Qué sentido tiene en organizaciones pequeñas medianas o grandes?

El fin de trabajar en ramas es evitar los conflictos y que solo el código que haya sido testeado y aprobado esté en la rama main

#### Pregunta: ¿Se producen conflictos al hacer 'git merge v0.2 -m "merge sin conflictos"'?

No, no se produce ninguno debido a que la información del fichero 1.txt en main contiene el contenido del 1.txt en v0.2 además de su propio contenido.
