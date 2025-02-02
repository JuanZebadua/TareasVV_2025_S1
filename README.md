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
Resuelva el ejercicio 2.24 explicando como obtuvo la salida Y

## Inciso 2
Utilizando la tabla de verdad a continuación, realizar las diferentes actividades.
![TablaDeVerdad]("Images/Captura de pantalla 2025-02-02 125714.png")
1. -Construya el circuito utilizando logic Friday o logisim. Muestre el procedimiento para generar las ecuaciones/circuito y logisim para simularlo. Utilice ambas estrategias (Sum of products && Products of a sum) mostrando las tablas de los minterms && maxtermns similar a las vistas en las presentaciones como por ejemplo:
![TablaDeVerdad]("Images/Captura de pantalla 2025-02-02 125949.png")
2. Seleccione en Digikey compuertas con empaquetado de superficie capaces de operar a 1.8V, muestre proceso de seleccion.
3. Calcule el margen de ruido en alguna de las secciones dadas las compuertas seleccionadas., muestre las dos compuertas estudiadas y un diagrama de volajes y calcule NMH + NML.
4. Calcule el critical path y shortest path mostrando los valores de t_pd y t_cd de las compuertas seleccionadas dentro del datasheet


## Inciso 3
Fuerce una compuerta a operar en su forbidden zone. Tome mediciones de voltaje con un osciloscopio y muestre lo peligroso de operar en esta región. Puede utilizar cualquier compuerta. Utilice el simulador de circuitos a su elección [tinker con compuertas y divisores de voltaje?].

## Inciso 4
Simule el siguiente circuito en su protoboard y simule su función:
![TablaDeVerdad]("Images/Captura de pantalla 2025-02-02 130057.png")
1. Compruebe su funcionamiento sea el esperado como el de un sumador completo de x1 bit .
2. Encuentre y mida el contamination + progration delay (Asuma para todas las compuertas un 𝑡𝐶𝐷=1𝑝𝑠 y 𝑡𝑃𝐷=2𝑝𝑠.
3. Extienda el circuito a un sumador de x2 bits completo (puede usar el circuito de su compañero) y mida de nuevo el contamination + propagation delay (para simulación, construya de forma herarquica e invoque dos instancias del sumador x1 en cascada).

## Inciso 5
Replique el circuito que genero un glitch:
![TablaDeVerdad]("Images/Captura de pantalla 2025-02-02 130249.png")