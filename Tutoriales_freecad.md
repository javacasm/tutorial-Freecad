# Tutoriales freecad 

## Tutoriales 61quick en youtube


## Obijuan
[enlace](http://www.iearobotics.com/wiki/index.php?title=Dise%C3%B1o_de_piezas_con_Freecad)

### 1/40 Programas CAD  https://www.youtube.com/watch?v=2_DbFzFV9D4
* TODO Buscar ejemplos (motor toyota, está en el programa de ingenieros)
* Software de pago: katia, solidworks, 
* Software libre: freecad, openscad (programando piezas), blender (más orientado a animaciones)

### 2/40 Primeros usos https://www.youtube.com/watch?v=ICHc7Z4vXXQ
* Bancos de trabajo ¿workbech? : part para diseñar ¿el resto?
* Navegación: ¿usar blender? gira la cámara: botón central gira y con shift se desplaza. El ratón preselecciona al pasar
* En data vemos los valores que podemos modificar
* La lupa centra (Fit All) y los otros  definen distintas vistas

Ejercicio: Monolito


### 3/40 Editando https://www.youtube.com/watch?v=dOdAtUmgW4k

* espacio permite ocultar/mostrar
* en la pestaña value podemos seleccionar el tipo de visualización, las aristas, colores, transparencias, etc...

Ejercicio: Crear un cubo dentro de otro


### 4/40 Trasladando https://www.youtube.com/watch?v=Mh8cC7F_R4k
* opciones view: EJES

Ejercicio: Creando q*bert


### 5/40 Fusiones https://www.youtube.com/watch?v=mntnhxidqoA

Arbol de dependencias: graphviz 

Fusión une las piezas, pero conserva su dependencia

Refinar "junta las piezas"
Podemos configurar para que siempre haga el refinado y la revisión de la geometría.

Ejercio: refinar q*bert y piezas de tetris.

### 6/40 Rotaciones https://www.youtube.com/watch?v=3FdmAnRRlzA

Al seleccionar tenemos una tarea que es Placement

Podemos hacer que se rote por cualquier punto

Si tenemos varios objetos seleccionados debemos marcar "Apply incremental changes"

Ejercicio: Casita

### 7/40 Diferencia (CUT) https://www.youtube.com/watch?v=3LsHR57grk0

* Fundamental que se haga en el orden adecuado TODO: Entenderlo porque tendría el sentido de que se quita del otro. ¿Qué significa que no tiene sentido?
* La operación se llama CUT.
* Al ser freecad paramétrico si modificamos cualquiera de las partes se modifica el resultado ¿qué ocurre si deja de ser válida la resta?

Ejercicio: lapicero

### 8/40 Aplicación: portalápices https://www.youtube.com/watch?v=XC5JMkl2B9k

* Definimos las ranuras (midiendo con el calibre)
* Los duplicamos y desplazamos as desplazamos

TODO: revisar la estructura final

Ejercicio: ranuras para tarjetas SD

### 9/40 Cilindros y pacman https://www.youtube.com/watch?v=jDaJpLadCjE

* Creamos cilindros
* Cambiamos la altura y el ángulo
* Creamos un 2º cilindro para hacer el ojo

Ejercicio: Tarta con sector externo
Ejercicio: ladrillo ¿cómo se hace para mostrar las medidas?

### 10/40 Repeticiones https://www.youtube.com/watch?v=bxKOFY2vgqM

* Workbench draft
* Array ![icono](http://www.iearobotics.com/wiki/images/d/df/Freecad-icono-array.png): permite generar colecciones de elementos en 3 dimensiones: definiremos la separación y el número de elementos en cada dimensión

Ejercicio: gofre 3D
Ejercicio: torre de catillo
Ejercicio: pieza de mecano
TODO ¿se pueden definir parámetros en las piezas? Para hacer piezas de mecano paramétricas.