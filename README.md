# Clase-11-de-mayo-de-2026
Defensa en clase

## Implementación de un Árbol Binario y un Grafo

Este proyecto contiene dos implementaciones fundamentales de estructuras de datos: un *Árbol Binario* y un *Grafo* no dirigido. Está desarrollado en Python y organizado para mostrar tanto la lógica recursiva como iterativa de los algoritmos de inserción, búsqueda, recorrido (inorden) y búsqueda en profundidad (DFS). El código es didáctico, ideal para entender el funcionamiento interno de estas estructuras.


## Árbol Binario
Un árbol binario es una estructura jerárquica donde cada nodo tiene como máximo dos hijos: izquierdo y derecho.

### Clase Nodo
- Representa cada elemento del árbol.
- Atributos: valor, izquierda, derecha.

### Clase ArbolBinario
- Gestiona la raíz del árbol y proporciona los siguientes métodos:

| Método | Descripción |
|--------|-------------|
| insertar(valor) | Inserta un valor en el árbol usando el método público. Llama al método recursivo interno. |
| _insertar_recursivo(nodo, valor) | Recursivo: ubica el nuevo nodo respetando la propiedad del árbol binario (menores a la izquierda, mayores a la derecha). |
| buscar(valor) | Busca un valor en el árbol. Retorna True o False. |
| _buscar_recursivo(nodo, valor) | Recursivo: recorre el árbol comparando valores. |
| inOrden() | Recorrido en orden (izquierdo → raíz → derecho). Devuelve una lista con los valores ordenados. |
| _inOrden_recursivo(nodo, resultado) | Recursivo: acumula los valores del recorrido inorden. |

