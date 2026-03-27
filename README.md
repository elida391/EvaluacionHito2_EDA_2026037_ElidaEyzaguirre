# EvaluacionHito2_EDA_2026037_ElidaEyzaguirre

1. Descripción del sistema permite:
Registrar estudiantes con nombre y código.
Atender estudiantes en orden de llegada (FIFO).
Mostrar la lista de estudiantes en espera.
Buscar estudiantes por nombre y mostrar su posición en la cola.
Salir del sistema mediante un menú interactivo.
El sistema está diseñado para simular la atención ordenada de estudiantes en una fila de espera.

2. Estructura usada y justificación
Se utilizó una lista enlazada simple implementada manualmente.
Cada nodo contiene:
Nombre del estudiante
Código del estudiante
Puntero al siguiente nodo

Justificación:
La lista enlazada simple permite manejar dinámicamente la cantidad de estudiantes sin necesidad de definir un tamaño fijo.
La inserción al final y la eliminación al inicio son operaciones eficientes para simular una cola (FIFO).
Cumple con la restricción de no usar estructuras de la STL (como vector o list).

3.Complejidad de las operaciones
Inserción (registrar estudiante):  
Se realiza al final de la lista → O(1)
Eliminación (atender estudiante):  
Se elimina el primer nodo → O(1)
Búsqueda (por nombre):  
Se recorre la lista hasta encontrar el estudiante → O(n)
Mostrar estudiantes:  
Se recorre toda la lista → O(n)

4. Instrucciones de compilación y ejecución
Compilación:
g++ main.cpp o gestion_estudiantes.exe
Luego, ejecuta el programa con:
gestion_estudiantes.exe
