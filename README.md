# Práctica de Hilos en Java

Sherlyne Alexia Vega Andrade 
2213042134

## Descripción

Esta práctica consiste en implementar un programa en Java que calcula la suma de los elementos de un arreglo utilizando varios hilos.

Para realizar el cálculo concurrente, se utiliza la interfaz Callable<Integer>, que permite ejecutar tareas y devolver un resultado. También se utilizan ExecutorService para administrar los hilos y Future<Integer> para recuperar los resultados de cada tarea.
Integer>.

## Funcionamiento

El programa realiza las siguientes operaciones:

1. Recibe como argumentos el tamaño del arreglo y el número de hilos.

2. Crea un arreglo de enteros.

3. Inicializa el arreglo con números aleatorios entre 0 y 99.

4. Imprime los elementos del arreglo.

5. Crea un grupo de hilos mediante ExecutorService.

6. Distribuye los elementos del arreglo entre las tareas.

7. Cada tarea calcula su suma parcial utilizando el método call().

8. Los resultados parciales se recuperan mediante

9. Se suman los resultados parciales para obtener la suma total.

10. Se muestra el resultado final y se cierra el grupo de hilos.

## Compilación

Para compilar el programa,se debe ejecutar el siguiente comando en la terminal:

bash javac SumaArreglo.java

## Ejecución

El programa recibe dos argumentos:

Primer argumento: tamaño del arreglo.

Segundo argumento: número de hilos que se utilizarán.

Ejemplo:
bash

java SumaArreglo 10 3

En este ejemplo, se crea un arreglo de 10 elementos y se utilizan 3 hilos para calcular la suma.
