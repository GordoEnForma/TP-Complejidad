# Informe del Trabajo Parcial
<center>Curso : Complejidad Algorítmica</center> <br>
Profesor : Luis Martín Canaval Sánchez <br>
Carrera : Ingeniería de Software <br>
Sección : CC41 <br>
Ciclo: 2021-1


## Integrantes
Gustavo Espinoza Mendieta (U20181E211) <br>
Mauricio Carmen Liñan (U201819787) 

## Introducción

El presente trabajo tiene como objetivo brindar sugerencias de solución a uno de los problemas más intrigantes y complicados en el mundo de la programación: <b>EL problema del Viajero.</b>
<br>

El proyecto por lo tanto va a brindar posibles soluciones a tan infame problema, que ha cautivado tanto a jovenes como expertos programadores, así como evaluar si dichas propuestas son o no eficientes en determinados contextos reales.

## Objetivos

- Proponer posibles soluciones al TSP
- Evaluar si las soluciones son o no viables

## Marco Teórico

### El problema del Viajero

El problema del viajero es uno de los problemas más complicados en el mundo de la computación, presenta el siguiente enunciado:  

<i>"Un vendedor viajero debe encontrar el camino único más corto que, dada una lista de ciudades y las distancias entre ellas, visita todas las ciudades una sola vez y regresa a la ciudad de origen."</i>

<img src="http://images.rapgenius.com/0e1ca854cbc30f33abc46108f2ba38f2.640x640x42.gif" alt="drawing" width="350"/>


### Grafos
Los grafos son un conjunto de nodos los cuales presentan vertices y aritas, los cuales nos ayudan a representar información de manera visual. 

### Fuerza Bruta
Uno de los algoritmos que hemos implementado como parte de nuestras propuestas de solución es uno basado en busqueda por fuerza bruta, que tiene como parte de sus caracteristicas permutar sobre todas las rutas para hallar todos los caminos posibles. 

### Backtracking
El siguiente algoritmo que proponemos es uno basado en Backtracking, el cual busca la mejor combinación posible, ya que si encuentra una solución "correcta"
aplica recursividad para encontrar otra propuesta, y en caso encuentre una solución "incorrecta" la recursividad retrocede un paso creando asi un arbol implícito en la que cada nodo es un estado de solución.


## Conclusiones

Despues de realizar las pruebas con varios distritos y centros poblados, hemos llegado a la siguientes conclusiones:

- El algoritmo por fuerza bruta al tener una complejidad O(N!) nos ayuda cuando la cantidad de datos es muy pero muy pequeña, siendo una opción inviable para representar los caminos entre varias ciudades ya que en la vida real no solo queremos conocer la mejor ruta entre 5 o 6 centros poblados.
- El algoritmo por backtracking tambien presenta una complejidad O(N!), lo que la vuelve una solución inviable para un uso real, siendo limitada a un uso didactico como parte del proceso de aprendizaje en el curso de complejidad algorítmica.
