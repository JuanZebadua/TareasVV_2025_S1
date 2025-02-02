<p align="center">
  <img align="center" alt="logo" src="Images/FING_Logo.png">
</p>

# Tarea C2 #

* **Tabla de Contenidos**
  * [Inciso 1](#inciso-1)
  * [Inciso 2](#inciso-2)
  * [Inciso 3](#inciso-3)
  * [Inciso 4](#inciso-4)
  * [Inciso 5](#inciso-5)

## Inciso 1
### Instrucciones
Resuelva el ejercicio 2.24 explicando como obtuvo la salida Y:
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 122954.png">
</p>

### Resolución
El inciso se resolvió en el enlace de [Youtube.](https://youtu.be/6Ba4DA_zyks)

## Inciso 2
### Instrucciones
Utilizando la tabla de verdad a continuación, realizar las diferentes actividades.
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 125714.png">
</p>

1. Construya el circuito utilizando logic Friday o logisim. Muestre el procedimiento para generar las ecuaciones/circuito y logisim para simularlo. Utilice ambas estrategias (Sum of products && Products of a sum) mostrando las tablas de los minterms && maxtermns similar a las vistas en las presentaciones como por ejemplo:
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 125949.png">
</p>

2. Seleccione en Digikey compuertas con empaquetado de superficie capaces de operar a 1.8V, muestre proceso de seleccion.
3. Calcule el margen de ruido en alguna de las secciones dadas las compuertas seleccionadas., muestre las dos compuertas estudiadas y un diagrama de volajes y calcule NMH + NML.
4. Calcule el critical path y shortest path mostrando los valores de t_pd y t_cd de las compuertas seleccionadas dentro del datasheet

### Resolución
El inciso se resolvió en dos videos de youtube, los cuales están en orden:
- El primer [enlace.](https://youtu.be/eaZxN3DiXYI)
- El segundo [enlace.](https://youtu.be/-QX8YDW_LkE)

## Inciso 3
### Instrucciones
Fuerce una compuerta a operar en su forbidden zone. Tome mediciones de voltaje con un osciloscopio y muestre lo peligroso de operar en esta región. Puede utilizar cualquier compuerta. Utilice el simulador de circuitos a su elección [tinker con compuertas y divisores de voltaje?].
### Resolución
Para realizar este ejercicio en el cual se desea ver en una simulación el comportamiento de una compuerta lógica al tener un input en su Forbidden Zone, se utilizó la aplicación **MultiSim**.
Ahora bien, dentro de la simulación hay varias compuertas lógicas, pero, se decidió utilizar una muy común por simplicidad, la cual es la compuerta **74HC08D** y tiene las siguientes características de nuestro interés.
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 134308.png">
</p>

No obstante, en el software de Multisim, no se puede indicar el voltaje de alimentación, sino que se peuden seleccionar compuertas con un nivel de alimentación fijo, por lo cual no se puede jugar mucho con este parámetro. Con esto en mente, se decidió utilizar una compuerta con alimentación de 2V. La simulación quedó armada del siguiente modo:
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 134557.png">
</p>

Ahora, una vez con este ecosistema, se corrió la simulación esperando tener resultados interesantes en la pantalla del osciloscopio cada vez que el voltaje del input variante pasara por los valores de la **Forbidden Zone**, pero, no fue el caso.
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 134809.png">
</p>

En el osciloscopio no se logra apreciar nunca un comportamiento como el que sucedería en la vida real al estar operando en la forbidden zone, por lo que se concluye que en la simulación este comportamiento no se puede observar. Ciertamente, es como si las compuertas tuvieran un Schmith Trigger a la hora de operar, lo cual se aleja a la vida real.

## Inciso 4
Simule el siguiente circuito en su protoboard y simule su función:
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 130057.png">
</p>

1. Compruebe su funcionamiento sea el esperado como el de un sumador completo de x1 bit .
2. Encuentre y mida el contamination + progration delay (Asuma para todas las compuertas un 𝑡𝐶𝐷=1𝑝𝑠 y 𝑡𝑃𝐷=2𝑝𝑠.
3. Extienda el circuito a un sumador de x2 bits completo (puede usar el circuito de su compañero) y mida de nuevo el contamination + propagation delay (para simulación, construya de forma herarquica e invoque dos instancias del sumador x1 en cascada).

## Inciso 5
Replique el circuito que genero un glitch:
<p align="center">
  <img align="center" alt="imagen" src="Images/Captura de pantalla 2025-02-02 130249.png">
</p>