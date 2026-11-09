# Act_3.4_Grafos-camino-mas-corto
Proyecto realizado en Java utilizando NetBeans, correspondiente a la actividad de optimización de rutas mediante grafos. Se desarrolla una interfaz gráfica con Java Swing para seleccionar nodos de origen y destino, elegir algoritmos de búsqueda y visualizar los resultados de las rutas.

## Equipo #2
CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo
Diseñar una interfaz gráfica que permita realizar la optimización de rutas entre diferentes nodos de un grafo, considerando los pesos de las conexiones y facilitando la comparación de resultados obtenidos mediante distintos algoritmos.

# Tecnologías utilizadas
Java
Java Swing
Apache NetBeans
Git y GitHub

# Características
Selección del nodo de origen.

Selección del nodo de destino.

Selección de algoritmos de optimización.

Ejecución de algoritmos para encontrar rutas.

Comparación de resultados entre algoritmos.

Visualización de la ruta encontrada.

Presentación del costo total de la ruta.

Registro de operaciones y pasos realizados.

Visualización del número de evaluaciones y descartes.

Opción para limpiar el registro de resultados.

Representación gráfica del recorrido mediante nodos y conexiones.

#Estructura del proyecto
Clase Grafo: representa la estructura de nodos y conexiones que se utilizan para encontrar rutas.

Clase Vertice: representa los diferentes puntos que forman parte del grafo.

Clase Arista: almacena las conexiones entre los nodos y sus respectivos pesos.

Algoritmo Dijkstra: permite encontrar la ruta de menor costo entre un origen y un destino cuando los pesos son no negativos.

Algoritmo Bellman-Ford: permite calcular rutas de menor costo, incluso con pesos negativos, siempre que no existan ciclos negativos alcanzables.

Interfaz gráfica: permite seleccionar los nodos, elegir los algoritmos y consultar los resultados de la optimización.

# Interfaz gráfica
La interfaz se realiza en NetBeans mediante componentes de Java Swing, organizando los paneles de selección de nodos, algoritmos, operaciones, registro y resultados. También contempla un espacio para representar gráficamente el recorrido y facilitar la visualización de la ruta óptima.
