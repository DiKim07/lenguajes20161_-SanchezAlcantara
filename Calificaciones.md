# Calificaciones

## Practicas

### Practica 1

Hay que tener cuidado con los casos base en primes no checa y se cicla
la función si dan un 0 como parametro y en mconcat se da un error al ejecutar

> (mconcat '() '())
. . car: contract violation
  expected: pair?
  given: '()
  
lo cual debería regresar simplemente '()

Tu implementación de any? y every? hacen uso de if anidados cuando para eso existe cond, aparte tu implementación de every? es erronea porque cuando tienes la lista vacía every? debe regresar #t

**Calificación: 9**

### Practica 2

Su implementación de MList es erronea solo acepta números cuando debía
aceptar cualquier tipo de valor. Su implementación de setvalueA es erronea están regresando una lista y no un arreglo nuevo con el valor alterado como deberia.
Su implementación de printML es erronea no están manejando correctamente los casos con listas MCons anidadas.
Su función mapML esta mal implementada.
No implementaron las funciones haversine, closest-building, buildings-at-distance y in-figure?

**Calificación: 6.5**

### Practica 3
Su implementación de bpm->zone es erronea.
No implementaron las funciones create-trackpoints, total-distance, average-hr,
max-hr, collapse-trackpoints.

**Calificación: 5**

### Practica 4

**Calificación: 0**

### Practica 5

**Calificación: 0**

### Practica 6

Dado que no hay herencia o polimorfismo tienen
dos puntos menos.

**Calificación: 4**

## Tareas

### Tarea 1

**Calificación: 0**

### Tarea 2

No subieron un PDF, la siguiente tarea sin PDF la calificación sera directo 0.

Problema 1: No indican como FAE tiene condicionales y recursion, solo avientan
la mención de Combinador Y y ya.
Problema 2: Su ejemplo es igual ya sea un lenguaje perezoso o glotón, da un
error de division por cero.

Problema 3: No dan el ejemplo ni indican cuales son las diferencias.

Problema 4: Nada que ver con lo que se pedia sobre evaluación perezosa y estado.

**Calificación: 0**

### Tarea 3

**Calificación: 0**