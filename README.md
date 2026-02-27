# 2-Evaulacion-Angel-L.-Angela-Y.-Damian-C.
En este repositorio dejamos como evidencia la ejecución de nuestra evaluación y proyecto por medio del desarrollo de programa basado en Python y el uso de las operaciones de enqueue(x), dequeue(), first() o  peek(), is_empty(), size().


Para el desarrollo de este programa y del proyecto 2m usamos los conceptos de:
-Pila (LIFO o Stack): Se caracteriza por ser una estructura creada para poder usar los metodos base (push, pop, peek, is_empty y size)
-Grafo no dirigido: Son las listas de adyacencia que usamos para poder implementarlo, es el diccionario de Python
-DFS: Es el algoritmo de busqueda en Profundidad que utilizamos en la Pila creada por nosotros para explorar el grafo.
Deteccion de Ciclos: Es on algoritmo que se usa para identificar su los caminos que recorre son cerrados al estar buscando el nodo "Padre".

## Implementación
Al estar desarrolando el código tuvimos que tomar algunas deciciones: 
- Al usar el ciclo "while" evitamos que el error de desbordamiento de la memoria "overflow"
- Usamos el método "set"para poder definir y guardar las definicioes o valores a una palabra clave para el programa, basciamente es asignar un valor a una palabra clave y que el programa lo recuerde.
-  De forma similar, usamos validaciones en la Pila creada para evitar errores sí se desea extraer informacón de los nodos, pero estos esten "vacios".


## Resultados:
En la libreta es posible observar como es que estan en orden para una mejor vusta de como es que funciona los códigos, un ejeplo de esto es:
- La correcta lectura de los nodos en un recorrido DFS
- La validación correcta de los grafos con o sin los True o false (con o sin ciclos)
