# Algoritmo de Dos Punteros - Proyecto de Ubicación de Invitados

## Descripción General
Este proyecto implementa el algoritmo de dos punteros para resolver un problema de organización de asientos para invitados. El programa encuentra pares de invitados cuyos nombres comienzan con la misma letra, lo que resulta útil para organizar la disposición de asientos en eventos.

## Cómo Funciona

### Descripción del Algoritmo
El programa utiliza dos punteros para recorrer un arreglo de nombres de invitados:
1. El puntero `inicio` comienza en el primer elemento
2. El puntero `siguiente` comienza en el segundo elemento
3. El algoritmo compara la primera letra de los nombres en ambas posiciones
4. Si coinciden, devuelve el par
5. Si no coinciden, ambos punteros avanzan una posición

### Ejemplo
```javascript
const invitados = ["Ana", "Carlos", "Cecilia", "Daniel", "Diana", "Eduardo"];