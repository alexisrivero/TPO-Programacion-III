# TPO-Programacion-III

## Algoritmos elegidos: Depth First Search(DFS) y Breadth First Search(BFS)

clase Vertice:  
La clase usa generics para que se pueda almacenar un objeto de cualquier tipo en el grafo.  
guarda el dato, un booleano para determinar si el vertice fue visitado o no y una lista de vecinos.

clase DepthFirstSearch:
implementa el metodo recorrer

recorrer:
recibe un vertice que sera el vertice inicial  
creamos una nueva pila y agregamos el vertice pasado en la firma del metodo  
mientras la pila no este vacia, desapilamos el primer elemento de la pila  
si el elemento actual no fue visitado lo marcamos como visitado  
para preservar el orden de los vecinos de los vertices hacemos reverse a la lista de vecinos  
y luego ingresamos a los vecinos a la pila


clase BreadthFirstSearch:  
implementa el metodo recorrer  
creamos una nueva cola y agregamos el vertice pasado en la firma del metodo  
mientras la cola no este vacia, desacolamos el primer elemento  
si el elemento actual no fue visitado lo marcamos como visitado  
finalmente agregamos a todos sus vecinos a la cola para que se siga repitiendo el procedimiento


recorrer:  
recibe un vertice que sera el vertice inicial

Integrantes:  
Elorz Brisa,  
Rivero Alexis,  
Dominguez Alan Thomas


<a href="https://github.com/OWNER/REPO/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=OWNER/REPO" />
</a>

